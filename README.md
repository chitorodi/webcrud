# webcrud
Crud  C#  .NET  con Entiframework


Utiliznado para el demo SQL 2019 y Visual Studio Community 2019


Script para tabla  tblEmpleados
----------------------------------------------------------------------------------------------------
USE [Empresa]
GO

/****** Object:  Table [dbo].[tblEmpleados]    Script Date: 07/04/2021 04:18:12 p. m. ******/
SET ANSI_NULLS ON
GO

SET QUOTED_IDENTIFIER ON
GO

CREATE TABLE [dbo].[tblEmpleados](
	[ID] [int] IDENTITY(1,1) NOT NULL,
	[Nombres] [nvarchar](50) NULL,
	[Apellidos] [nvarchar](50) NULL,
 CONSTRAINT [PK_tblEmpleados] PRIMARY KEY CLUSTERED 
(
	[ID] ASC
)WITH (PAD_INDEX = OFF, STATISTICS_NORECOMPUTE = OFF, IGNORE_DUP_KEY = OFF, ALLOW_ROW_LOCKS = ON, ALLOW_PAGE_LOCKS = ON) ON [PRIMARY]
) ON [PRIMARY]
GO
-------------------------------------------------------------------------------------------------------------------------
