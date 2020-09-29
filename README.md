# MoveListv.2

This is code Challenge Day 16

# Challenge Goals

1. db.js file, controllers, routers, 그리고 templates 이 이미 준비되어 있습니다.
2. With the provided blueprint, make an app that has this exact output:

# Conditions

1. You need to create the route, controller and .pug template for the page /add.
2. The /add page should be a form with three inputs: title, synopsis, genres. title and genres should be inputs and synopsis should be a text area.
3. This form should POST to a page with a controller that calls the addMovie function and adds the movie with the fields from the form.
4. The addMovie function takes one argument, that argument should be an object containing title, synopsis, genres.
5. After the movie is created the user should be redirected back to /
6. Do everything in maximum TWO controllers.
7. The form has to do a POST request.
8. Use .pug
9. You need to take the genres input from the frontend and learn how to turn it into an array on the backend. Separate it by commas ( , )Drama, Comedy, Accion -> ["Drama", "Comedy", "Action"]
10. Not allowed to type the array from the frontend.
11. The app must behave exactly like the video
