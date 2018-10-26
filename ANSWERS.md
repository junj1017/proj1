# Q0: Why are these two errors being thrown?
Because we do not have a pokemon model.
# Q1: How are the random Pokemon appearing? What is the common factor between all the possible Pokemon that appear? *
From the rails db:seed. The random pokemon is appearing from the seed file. The common factor is that they are the most popular.
# Question 2a: What does the following line do "<%= button_to "Throw a Pokeball!", capture_path(id: @pokemon), :class => "button medium", :method => :patch %>"? Be specific about what "capture_path(id: @pokemon)" is doing. If you're having trouble, look at the Help section in the README.
It makes a button "throw a pokeball", and when a user clicks on a button, then the function capture from pokemons is called.
After calling the capture function, it updates/patches the pokemon by assigning it to a user.

# Question 3: What would you name your own Pokemon?
Harambe

# Question 4: What did you pass into the redirect_to? If it is a path, what did that path need? If it is not a path, why is it okay not to have a path here?
I redirected to pokemon.trainer. It does not need a path because the page redirects to the original page that was already there. It stays on the page /trainer.

# Question 5: Explain how putting this line "flash[:error] = @pokemon.errors.full_messages.to_sentence" shows error messages on your form.

It errors when a specific pokemon already exists, so it uses that pokemon to flash the error.
# Give us feedback on the project and decal below!
Project was really fun! Decal is going well, but I hope it's more interactive.

https://github.com/junj1017/proj1


# Extra credit: Link your Heroku deployed app
