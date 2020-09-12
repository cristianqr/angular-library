# Angular Library
This project is an example of how to create an angular library and test through an angular application.

## How was created it?
1. Create a workspace:
`ng new angular-library --create-application false`

2. Create a library:
`ng g library angular-library`

3. Create an application to test the library:
`ng g application library-test`

4. Create a hello-world module:
`ng g m hello-world --project angular-library --routing`

5. Create a hello-world component:
`ng g c hello-world --project angular-library`

6. Load the library into library-test application through a route
