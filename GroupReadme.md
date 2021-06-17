Things covered in groups.py

1.  Giving Access of a folder to a group -\> This method can be called
    to give access of a folder to a group. For this we need the id of
    the folder whose access is to be given and the id of the group whom
    the access is being given to. Call the method with these inputs
    value and access will be given to the group.

2.  Giving Access of a folder to a User -\> Similar as above, instead of
    group id just pass the user id to whom the access is being given to.

3.  Inviting Users to join a Group -\> In a Group, there are Admin,
    Moderators and Members. All three can send invitations to other
    users to join the group by this method. Only Admin can directly join
    the users if he wants. This can be done by setting the input field
    force to be true. Else keep it false for sending invitations.

4.  Deleting a Member from group -\> A member can be removed from the
    group by this. This can be called only by the moderators or Admins.


