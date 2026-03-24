CREATE DATABASE contactesad;
GO

USE contactesad;
GO

CREATE TABLE Contacts (
    Id INT IDENTITY(1,1) PRIMARY KEY,
    Name VARCHAR(50) NOT NULL,
    LastName VARCHAR(50) NOT NULL,
    Address VARCHAR(100),
    Email VARCHAR(100),
    Gender VARCHAR(10),
    Age INT,
    IsFavorite BIT
);
