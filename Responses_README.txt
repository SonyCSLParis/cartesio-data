The datasets contains the responses of user to the cartesio experience.
Each record is composed of:
id (str): a unique identifier for each response.
session_id (str): a unique identifier for the session. A session includes all the interactions from login to log off.
user_id (str): a unique identifier for each user. This identifier is the same as the on on the user table and can be used to
    match users to their responses.
article_id (str): a unique identifier for each article in the dataset. IMPORTANT ids beginning with the letter 'f' have
    been identified as fake by expert fact-checkers. So 'aid_'<num> is an article for which we do not have additional
    information, 'f_aid_'<num> is known to be disinformation.
created_at (time): year-month-day hour:minute:second of the recorded response
position (int): this field counts the number of interactions within a given session. Each response will have a certain
    position withing the dataset.
trust (int): the trust score assigned by the user to the news item.
clicked_read_more_at (time): within the experience it was possible to display the news item in a short version with title and
    first lines, or a longer version. In order to see the longer version the user clicked on a button. The time of this
    action is recorded in this field. year-month-day hour:minute:second