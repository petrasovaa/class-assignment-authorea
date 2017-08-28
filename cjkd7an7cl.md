It is often very useful to edit a document offline, for example if youThese are the steps to use Authorea and GitHub together:

1. I created a new repository on Github:
https://github.com/petrasovaa/class-assignment-authorea and created README.md file. I first tried without any file, but it the connection was not working, although I am not sure that was the problem.
1. Then in Authorea I clicked on the gear symbol on rhe right and selected GitHub.
1. At this point you can setup GiHub integration automatically, but I wanted to have the integration under my control, so I chose the manual setup.
1. I first generated SSH key pair. A dialog opened and I copied the public key and in the Settings of the new GitHub repository I selected _Deploy key_ and added new key, where I copied the Authorea generated public key.
1. Still in GitHub I copied the SSH URL of the repository (not the HTTPS) and pasted it into appropriate field in Authorea GitHub settings.
1. Then I copied the webhook URL from Authorea and in GitHub repository settings I added it to _Webhooks_ section. I pasted there the URL and kept the rest as is it was.
1. Back in Authorea, I kept the branches as they were suggested. You can change the names of the main branch and the branch used when conflict happens.
1. Finally submit and add this point it sould start to syncronize.

As you can see when you look into the history of my repository, as I type, changes are pushed to GitHub. The history is not very useful to review in this case since it pushes really small changes very often. It also must be said, I had problems in the beginning to set up this connection, because Authorea was coplaining about merge conflicts, but that was later resolved, probably by creating a file in the repository.
