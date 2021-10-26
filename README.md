# Free And For Sale
Created by:

Technologies Used:

Motivation

Sublet-Me was initially created as a platform to help students easily find sublets in the Waterloo area. Even though there were different groups on Facebook, these groups are often unrealiable and do not have a proper sorting system.

Sublet-Me attempts to solve this problem by allowing students to easily transfer their postings directly from social networking platforms to our platforms through the Google Vision API.

How we built it

Our frontend is built using React and MDBReact for styling different components on our platform. Our backend uses MongoDB, Express and Node for storing and accessing the sublet data. We also used multer as a way to store the images on the local server before uploading the data to MongoDB. In order to have a map view of the sublet and its distance/time from nearby locations, we used Google Maps, Google Geocoding, and Google Distance Matrix to display and load the information. To allow users to transfer their posts from Facebook to our website, we used Google Cloud Vision to scan the post, detect any keywords, and autofill that information on our forms. For account registration and information, we used Auth0 so that users can log in with their Google accounts to create the sublets. Finally, in order for users to directly SMS a tenant on the website, we used the Twilio API.
