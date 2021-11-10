# Challenge-one

Preparation task for your upcoming interview

This home assignment is a preparation step for your upcoming interview with our
engineers. The interview will be around the code you wrote during this assignment.
Please be aware that we do not expect you to work on this for more than 2 hours.
Please read the requirements carefully before starting to code. Feel free to ask any questions
regarding or the scope of the assignment.

Requirements
Hi! Welcome to CloudCorp!
Extensive market research has shown that our users are tired of sending gigantic full-size
images to their customers. They are clamoring for a service that can manipulate remote
images on demand. Their primary concern is reducing bandwidth usage when fetching
images for their users.


Our users, who already host their own images, need a service that will transform and deliver
these images on-demand (no pre-processing on their side) so the transformed images can
be used from an <img> tag on a webpage. Your task is to build a service that exposes an
API implementing an on-demand resize transformation. You will need to design the shape
of such an API. The endpoint is going to be used inside an <img> tag on a webpage like in
the following "<img src="https://your-imaginary-api.com/...something here
that you need to figure out...">. "

The API will receive which image to resize and
the desired resulting size. Note that the service is not intended to store any image at all, just
resize on demand the one specified in the input parameters.
For any doubts on these requirements or the scope of the assignment, please contact us
as soon as possible so we can clarify them.

Technical constraints
We expect you to build a robust and safe implementation, as free from bugs as possible. You
can assume that incoming requests have already been authorized, but of course data
validation and security should always be taken into consideration.
These are the only technical constraints that your solution must meet:
● The service must run in Node.js. Please use NPM instead of Yarn.

● You can use either Javascript or TypeScript. Choose the one you are more
comfortable with, it will not influence our assessment.
● For the server itself use either Express (https://expressjs.com/) or Hapi
(https://hapi.dev/).
● For the image manipulation use the Sharp library
(http://sharp.pixelplumbing.com/en/stable/)
Besides that you are free to install any other packages you need to accomplish your goals.
We're all programmers. We all use StackOverflow and Google, and we all forget the
argument order of Array#reduce. Please develop like you normally would and use Google,
MDN, whatever you need.
