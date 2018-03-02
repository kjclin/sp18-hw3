## Questions

1. What does the second 'nil' argument in the line 6 text_field_tag of teachers/new.html.erb represent?
From apidock: text_field_tag(name, value = nil, options = {}) Sets the value to nothing in order to set a default value. 

2. Go to `localhost:3000/teachers` in your browser; why does this not work?
ActionController::RoutingError (No route matches [GET] "/teachers"):
Most likely it's because we didn't come to this page after submitting a form, so there is no data and it errors out. 

3. What type of request did your browser just perform?
GET

4. Go back to `localhost:3000/teachers/new`; submit the form again. What URL do you end up at?
The form for me to submit name, course, grade level
http://localhost:3000/teachers

5. Why does `localhost:3000/teachers` work now?
Yes. 