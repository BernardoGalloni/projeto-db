-- Script DML: Operações de dados

-- INSERT
INSERT INTO Clientes (nome, email, telefone)
VALUES ('Bernardo Galloni', 'b.g.menichelli@uni9.edu.br', '99704-4006');

INSERT INTO Planos (nome, preco)
VALUES ('Plano A', 25.00);

INSERT INTO Assinaturas (cliente_id, plano_id)
VALUES (1, 1);

-- UPDATE
UPDATE Planos
SET preco = 30.00
WHERE id = 1;

-- DELETE
DELETE FROM Assinaturas
WHERE id = 1;