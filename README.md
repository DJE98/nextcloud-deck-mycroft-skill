# Mycroft AI Skill for the nextcloud deck cloud application

## Comand for control

### Boards 
User: Get a list of boards\
Reply: The following boards are available $boards


User: Create a new board with title $title (and color $color)\
Reply: The board $title  was successful created.\
Reply: The board $title was not created, because [Error code]


User: Get board details from $title\
Reply: Which board details do you want to know?\
Reply: color, archived, labels, acl, permissions, users, deletedAt,users, deletedAt

User: color\
Reply: The board color is $color

User: archived\
Reply: The board is archived.\
Reply: The board is not archived.

User: labels\
Reply: The has the following labels: $labels:title, ...

User: acl\
?

User: permissions\
Reply: You have the right to read/edit/manage/share

User: users\
Reply: The following users are on the board $users:displayname, ...


User: deletedAt\
Reply: The board was deleted at $deletedAt\
Reply: The board was not deleted


User: Archive board $title\
Reply: The board $title was archived\
Reply: The board $title was not archived because [Error code]


User: Delete board $title\
Reply: The board $title was deleted\
Reply: The board $title was not deleted, because [Error code]


User: Restore delted board $title\
Reply: The board $title was restored.\
Reply: The board $title was not restored, because [Error code]


User: Add new acl rule\
Reply: For which type of participant?\
User: User/Group/Circle

Reply: For which User/Group/Circle?\
User: $title

Reply: Do the User/Group/Circle the permission to edit?\
User: Yes\
User: No

Reply: Do the User/Group/Circle the permission to share?\
User: Yes\
User: No

Reply: Do the User/Group/Circle the permission to manage?\
User: Yes\
User: No
