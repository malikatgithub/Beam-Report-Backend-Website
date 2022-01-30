
<p align="center"><img src="https://scontent.fkrt5-2.fna.fbcdn.net/v/t1.6435-9/118497509_1001480233620251_7873125946178401628_n.png?_nc_cat=110&ccb=1-5&_nc_sid=09cbfe&_nc_eui2=AeFphoaffqNCvVR9_GkWpMHEzU-cDW8OTtLNT5wNbw5O0qjHXlWBFQetEIrNCWvlOPf5Uy7NWvIEKYTjOK8bA-Tx&_nc_ohc=-0oOyBM8DwoAX_F_3P2&_nc_ht=scontent.fkrt5-2.fna&oh=00_AT8SJUBl7HVPB94wkrLjm9z8hvyCKjmraJbF_PvdIvx65A&oe=621DD7B4"></p>

<p align="center" style="margin-bottom:150px">
PRIVILEGE.SD | MALIK KHALIL MOHAMED | DEVELOPER
</p>


# Beam-Report-Backend-Website
A website Backend Configurations and Management v.2.0.1


<b style="margin-top:100px"> A password protected administration area that allows the privileged users to: </b>
- Add news articles
- Add categories
- Assign articles to categories
- Edit an existing article e.g. changing the title or text
- Delete articles from the website
- Edit category names
- Delete categories


<b style="margin-top:100px"> A publicly visible front-end that allows simple users to </b>
- Browse all the news articles displaying newest first
- View a list of news categories in the drop-down menu in the supplied HTML layout
- Click on one of the categories to view news articles in that category only
- Add a comment to a news article
- See comments added to that article by other users. Comments are visible on the news article page, and only comments for the selected article are visible.

<b style="margin-top:100px">  Additional Enhancements: </b>
- Multi-layered user privileges system with admin, author, user and guest.
- Moderation of comments. When a comment is added, it's placed in a holding area in the administration area for administrator approval before appearing on the website
- Ability to upload an image for an article otherwise the default will appear
- Social media buttons allowing users to easily share news articles
- Allow searching news articles by typing in a search text box
- Allow administrators to manage administrator accounts. Admins are able to create, update, and delete other admin/author users who can then log in and post stories. Stories posted are associated with user who posted them. The news article's author is visible on the news article's page. Soft Delete is implemented (meaning the account becomes inactive but still exists in the database with the ability to be restored)
- Securely store passwords with hashing
- Users must login to post comments
- Users are able to reply to a comment effectively allowing nested comments
- Users can be signed to the newsletter and receive notifications whenever a new article is posted (non-functional as it needs a mail server but implemented in code)
- The ability to click on a user and see any comment they have made
- The ability to see all news articles posted by a specific author

