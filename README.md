# SqlLastMessages
sqlite query for get last messages for all users

This query to select last messages for every users in personal chats with exclude self user
Table description
id - id of message
created - date of message
from_user_id - id of user who sent message
to_user_id - id of user who recieved message
'11111' - id of excluded user (change to real self user id)
