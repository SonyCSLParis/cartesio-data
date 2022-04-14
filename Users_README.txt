This dataset contains the information on users of the Cartesio platform.

Each record contains:
id (str): a unique identifier for each user. Can be used to identify users also in the responses table.
role (str): FORSE LO LEVO
created_at (time): the time at which the user was created. year-month-day hour:minute:second.
age_range (int): an identifier of the age interval of the user. 1 ="<18"; 2 =">18-20"; 3=">21-24";4=">25-34";5=">35-44";
    6=">45-54"; 7=">55-64"; 8=">64".
gender (int): the self reported gender of the user. 1='male', 2='female'.
degree (int): this field indicates the maximum level of education attained by the user. 0="elementary"; 1="average";
    2="superior"; 3="university"; 4="post university".
location (str): the region of residence of the user.