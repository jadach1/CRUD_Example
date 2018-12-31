EVERYTHING SHOULD BE READY AND SET UP ALL YOU NEED TO DO IS HAVE POSTGRESQL INSTALLED AND HAVE THE FOLLOWING TABLE CREATED

create table person (
id serial,
name character varying(22),
age integer,
CONSTRAINT person_pkey PRIMARY KEY (id)
);

once you have cloned the repo you can run the command "node server.js" and proceed to https://localhost:3000/ , you will first need the correct password in the string located inside server.js

NOTE:  node version upon creation was v10.14.1
