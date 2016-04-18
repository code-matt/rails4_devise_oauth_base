##TODO:

###Finish Readme
<p>
/users/sign_up
/users/sign_out
/users/sign_in

^ will work out of the box. You need to configure your github keys mentioned
below or add different providers to oauth. Its pretty simple adding them though.
</p>
<p>
Right now this is has github oauth added to it. Take a look in
config/initializers/devise.rb for where to add more. You will need
their oauth gem as well. Ex: gem 'omniauth-github'
</p>
