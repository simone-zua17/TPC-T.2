<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tabela de Estudantes</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            background-color: #1c1c1c;
            color: white;
        }
        h2, h3 {
            text-align: center;
        }
        nav {
            text-align: center;
            margin-bottom: 20px;
        }
        nav a {
            color: #007bff;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
            background-color: #2c2c2c;
            border-radius: 10px;
            overflow: hidden;
        }
        th, td {
            border: 1px solid #444;
            padding: 12px;
            text-align: center;
        }
        th {
            background-color: #444;
            color: white;
        }
        tr:nth-child(even) {
            background-color: #333;
        }
        tr:hover {
            background-color: #555;
            transition: 0.3s;
        }
        .form-container {
            margin-top: 30px;
            background-color: #222;
            padding: 20px;
            border-radius: 10px;
            width: 60%;
            margin-left: auto;
            margin-right: auto;
        }
        input, select, button {
            margin: 8px 0;
            padding: 12px;
            width: 100%;
            border-radius: 5px;
            border: none;
        }
        input, select {
            background-color: #333;
            color: white;
        }
        button {
            background-color: #007bff;
            color: white;
            cursor: pointer;
            font-size: 16px;
        }
        button:hover {
            background-color: #0056b3;
            transition: 0.3s;
        }
        @media (max-width: 768px) {
            .form-container {
                width: 90%;
            }
        }
    </style>
</head>
<body>
       

    <h2>Tabela de Estudantes</h2>
    <table>
        <tr>
            <th>ID</th>
            <th>Nome</th>
            <th>Idade</th>
            <th>Turma</th>
            <th>Email</th>
            <th>Telefone</th>
            <th>Nota Final</th>
            <th>Situação</th>
        </tr>
        <tr>
            <td>1</td>
            <td>Simone Zua</td>
            <td>18</td>
            <td>18 BNI</td>
            <td>simonezua14@hotmail.com</td>
            <td>924222612</td>
            <td>15</td>
            <td>Aprovado</td>
        </tr>
        <tr>
            <td>2</td>
            <td>Fredy Pedro</td>
            <td>17</td>
            <td>18 BNI</td>
            <td>F@email.com</td>
            <td>923456789</td>
            <td>16</td>
            <td>Aprovado</td>
        </tr>
        <tr>
            <td>3</td>
            <td>Alexandre Adula</td>
            <td>18</td>
            <td>18 BNI</td>
            <td>A@email.com</td>
            <td>923123456</td>
            <td>7.8</td>
            <td>Aprovado</td>
        </tr>
    </table>

    <div class="form-container">
        <h3>Adicionar Estudante</h3>
        <form>
            <input type="text" placeholder="Digite o ID">
            <input type="text" placeholder="Digite o Nome">
            <input type="number" placeholder="Digite a Idade">
            <input type="text" placeholder="Digite a Turma">
            <input type="email" placeholder="Digite o Email">
            <input type="tel" placeholder="Digite o Telefone">
            <input type="number" step="0.1" placeholder="Digite a Nota">
            <select>
                <option value="Aprovado">Aprovado</option>
                <option value="Reprovado">Reprovado</option>
            </select>
            <button type="submit">Adicionar Estudante</button>
        </form>
    </div>

</body>
</html>


