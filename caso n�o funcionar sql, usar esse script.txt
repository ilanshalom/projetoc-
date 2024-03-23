create database faculdade;
use faculdade;

CREATE TABLE `aluno` (
  `nome` varchar(45) NOT NULL,
  `idade` int NOT NULL,
  `rgm` int NOT NULL,
  `curso` varchar(45) NOT NULL,
  PRIMARY KEY (`rgm`)
);

CREATE TABLE `curso` (
  `cod` int NOT NULL,
  `nome` varchar(45) NOT NULL,
  `descricao` varchar(45) NOT NULL,
  `duracao` varchar(45) NOT NULL,
  PRIMARY KEY (`cod`)
);

INSERT INTO `aluno` VALUES ('Vinicius',24,12151478,'ADS'),('Ilan',28,15789869,'ADS'),('Matheus',30,15987535,'ADM'),('Angel',35,87546585,'ADS');
INSERT INTO `curso` VALUES (1,'ADS','Análise e desenvolvimento de sistemas','2 Anos'),(2,'ADM','Administração','4 Anos'),(3,'ENF','Enfermagem','4 Anos'),(4,'ARQ','Arquitetura e Design','8 Anos');