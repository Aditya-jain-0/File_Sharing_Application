"# File_Sharing_Application" 

A Password protected file sharing application
if one uploads a files and set the password
then the other user requires password in order to download the file 

After user uploads the files the file name,times downloaded ,password (stored in encrypted format using bcrypt library) stored inside the monogdb database

multer :- handling multipart/form-data , which is primarily used for uploading files.

here password can be optional depends on user whether to keep password or not

requirements :- express,moongoose,nodemon,bcrypt,multer