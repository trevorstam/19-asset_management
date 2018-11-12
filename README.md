## LAB 19: Asset Management

#### Author
Trevor Stam

### Assignment
* create an AWS account
* create an AWS Access Key and Secret
  * add the Access Key and Secret to your `.env` file
* create a new model that represents a file type that you want to store on AWS S3
  * ex: `.mp3`, `.mp4`, `.png`, etc
* create a test that uploads one of these files to your route
* use `multer` to parse the file upload request
* use the `aws-sdk` to assist with uploading
* create user, profile, and image models, with relational connections
* combine your API, Auth, and Upload modules into a single application
* Following a sign-in, create a profile model entry, connected to the user id
* Following the upload of an image, create a new record in the image collection, connected to the profile
* Using populate, return a user's full profile AND a list of all images they've uploaded as a JSON object
* Later, we can use this API to feed a Pinterest-like application.

### Dependencies
aws-sdk,
babel-env,
babel-eslint,
babel-register,
bcrypt,
cors,
dotenv,
eslint,
express,
fs-extra,
http-errors,
jest,
jsonwebtoken,
mongodb-memory-server,
mongoose,
morgan,
multer,
require-dir,
supertest

### Getting Started
- fork and clone repo
- Get node server running
- Make sure MongoDB is running simultaneously
- Use Postman to test the routes
