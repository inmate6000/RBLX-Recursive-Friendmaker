# RBLX-Recursive-Friendmaker (COMING SOON)
Specify a user id, and then will friend everyone within X specified levels. 

Example:

RecursiveFriendMaker(3)
# WILL WALK DOWN TREE (User, All of Users's Friends, All of User's Friend's Friends, ...)
EXAMPLE WITH A USER WITH 5 FRIENDS FOR LEVEL 3

program runs -> Friends user -> Friend's userFriends[5] -> Finds userFriends[5]'s FriendsList => curFriendList[0] -> Friends curFriendList[0][0] -> Walks up one level -> Finds userFriends[4]'s FriendList => curFriendList[1] -> Friends curFriendList[1][0] -> Walks up one level -> etc.
