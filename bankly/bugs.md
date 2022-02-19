

Bug #1 : authUser function on auth.js middleware had 'jwt.decode' instead of 'jwt.verify'

Bug #2 : user delete method does not need to return true

Bug #3 : User.js getAll function requires username/password. 

Bug $4 : Users.js get '/' route returning more information that the docs say it should Returns email and phone when it should only return username , first_name , last_name. Fixed on User.js
