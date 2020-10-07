# Assignment for FullStack Web Developer

Problem:

Create a web application to scrap the popular videos from Youtube, save them into the database, and list down the video on a webpage from the database.

 Follow the details of the problem below:

- Create below API endpoint:
  - One endpoint is to retrieve the popular videos from YouTube: &quot;https://www.youtube.com/feed/trending&quot; and save them into the database.
  - One endpoint should return the videos list from the database.
  - Another endpoint should return the detail about a single video. The video detail API response should include &quot;video title&quot;, &quot;description&quot;, &quot;video URL&quot;, &quot;video thumbnail&quot; in all available sizes, &quot;video view count&quot;, &quot;likes&quot; and &quot;dislike&quot; count, channel title, channel description, channel thumbnail in all available sizes and channel subscribers.

- Create a Frontend of the Web Application:
 This web application should have two pages.
  - One is the landing page, where you have to show the list of the available popular videos from the API (#2nd API endpoint).
  - The landing page should have a link/button by clicking that popular video will be retrieved again and saved into the database. Please make sure that the video which is already available should not create a new entry in DB. Only update the details of such videos.
  - The second page will be the details of the video. When clicking on any video from the landing page, the user should be redirected to this page of your application where you have to display information about the video and embed the respected video that should autoplay once the user comes on the page.

Keep in mind the below points:

- This API should be developed using any Javascript Library/Framework, for example, Node.JS, express.js, sail.js, etc.
- You can use any database as per your convenience, for example, MySQL, MongoDB, etc.
- The frontend of the App should be developed using HTML/HTML5, CSS/CSS3, JS, and PHP. The webpages should be rendered server-side using PHP.

Submission:

- Share Source code link GitHub.
- Share the URL where you have hosted the project (mandatory).
- Git repository should contain a good README.txt​.
- Decent Application code and DB structure (preferred).
- Application code should be neat and clean (not contain un-used or commented code /warning).
- Error or Exception handling.
- Instructions to set up and run the solution on a LINUX environment (preferred).
- (Optional) Dockerizing the application will earn you some extra points.