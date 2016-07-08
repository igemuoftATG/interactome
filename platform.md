# Synthetic Biology Interactome
IAAS: Interactome as a Service

Discussion and proposal for assembling a software capable of delivering on a self-hosted social-network-forum like application. An **interactome** for discussing synthetic biology from all perspectives and users. Faculty, grad students, professors, startups, companies, governments and education experts should all feel comfortable and secure using the software. Used for distributing information and powering discussion on


Ideas
- weekly contributed markdown newsletter content, gets sent out if approved same time each week
  * good because multiple people can work on the weekly newsletter
  * bad because they will need to have a GitHub/GitLab account and be collaborators. doing this in-house with GitLab may help, but then people need to create a GitLab account under our org.

See [awesome-selfhosted#social-networks-and-forums](https://github.com/Kickball/awesome-selfhosted#social-networks-and-forums) for a list of potentially applicable open source softwares.

re existing open source software

## Features
- User login + iGEM login
- Papers
- Discussion Forum
- Email newsfeed (Self-hosted or mailchimp)
- Video Conference (Hangout)
- Events + Calendar

### Possible Softwares
<!-- confused how to write a markdown table? -->
<!-- see: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#tables -->
<!-- each row must be on one line. best editing environment will be a text editor with soft-wrap on -->
<!-- plus use link names like here to keep it cleaner -->
| APIs                            | Description                                                             | Priority | Team  |
|---------------------------------|-------------------------------------------------------------------------|----------|-------|
| Login: <br> [Google Client Api] | Allow users to login with google accounts                               | High     | Team1 |
| Papers: <br>  Undecided         | Have a way for users to share their papers                              | High     | Team1 |
| Forum: <br> [NodeBB]            | Item Two                                                                | High     | Team2 |
| Loading Pages: <br> [BigPipe]   | Divides up the page into pagelets for faster loading (used by facebook) | Low      | Team3 |
| Database: <br> [PostreSQL]      | Database to store newsfeed                                              | High     | Team4 |
| Email: <br> [Mailchimp]         | Send Emails with updates                                                | High     | Team4 |


### Server
Server is going to be provided by Ontario Genomics. There will be an IP available hopefully by the July 15th.

## TODOS
- Find better software
- define project milestones
- Suggestions for improvements on the interactome. open a slack channal


[Google Client Api]: https://github.com/google/google-api-nodejs-client/#oauth2-client
[NodeBB]: https://github.com/NodeBB/NodeBB
[BigPipe]: https://github.com/bigpipe/bigpipe
[PostreSQL]: https://www.postgresql.org/
