# MoveListv.2

This is code Challenge Day 16

# Challenge Goals

1. db.js file, controllers, routers, 그리고 templates 이 이미 준비되어 있습니다.
2. With the provided blueprint, make an app that has this exact output:

# Conditions

- [x] You need to create the route, controller and .pug template for the page /add.
- [] The /add page should be a form with three inputs: title, synopsis, genres. title and genres should be inputs and synopsis should be a text area.
- [x] This form should POST to a page with a controller that calls the addMovie function and adds the movie with the fields from the form.
- [x] The addMovie function takes one argument, that argument should be an object containing title, synopsis, genres.
- [x] After the movie is created the user should be redirected back to /
- [x] Do everything in maximum TWO controllers.
- [] The form has to do a POST request.
- [x] Use .pug
- [x] You need to take the genres input from the frontend and learn how to turn it into an array on the backend. Separate it by commas (,)Drama, Comedy, Accion -> ["Drama", "Comedy", "Action"]
- [x] Not allowed to type the array from the frontend.
- [x] The app must behave exactly like the video
