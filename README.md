##TODO:

###Finish Readme
<p>
```
/users/sign_up
/users/sign_out
/users/sign_in
```
^ will work out of the box. You need to configure your github keys for its
link on the sign in page to work. Adding different oauth providers
is just a few lines.
</p>
<p>
Right now this has github oauth added to it. Take a look in
config/initializers/devise.rb for where to add more. You will need
their oauth gem as well. Ex: gem 'omniauth-github'
</p>
