# mulesoft-Internship

CREATE TABLE movies (
  Name TEXT NOT NULL,
  Actor TEXT NOT NULL, 
  Actress TEXT NOT NULL, 
  Director TEXT NOT NULL, 
  Year_of_release NOT NULL
);
INSERT INTO movies VALUES ('Avatar', ' Sam Worthington', 'Zoe Saldanal', 'James Cameron', 2009),('The Dark Knight Rises', 'Christian Bale', 'Anne Hathaway','Christopher Nolan',2012),('Skyfall','Daniel Craig','Naomie Harris',' Sam Mendes',2012);
SELECT * FROM movies;
SELECT Name FROM movies where Actor="Daniel Craig";
