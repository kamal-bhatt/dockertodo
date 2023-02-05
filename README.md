# dockertodo
A sample docker based application. The application is the todo.


# docker best practice
Ex - nodejs
use specific docker images
use specific image versions
use small sized official images
optimize caching layer - use frequent changes steps into the end
use .dockerignore file
use multi stage build to seprate the build and production images
Check which OS user start a application. Do not use the root user instaed of least privilige user
Validate images for security best practice

To go to the bash terminal inside docker container
docker exec -it containerid bash