# Sistema-de-Gerenciamento-de-Estudantes-em-Python---Idex


<!DOCTYPE html>

<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>README - Sistema de Boletim Escolar</title>

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Segoe UI',sans-serif;
}

body{
    background:#0f172a;
    color:white;
    line-height:1.6;
}

header{
    text-align:center;
    padding:60px;
    background:linear-gradient(135deg,#06b6d4,#14b8a6);
}

header h1{
    font-size:3rem;
}

header p{
    margin-top:10px;
    font-size:1.2rem;
}

section{
    padding:40px 10%;
}

.card{
    background:#1e293b;
    padding:25px;
    border-radius:15px;
    margin-bottom:25px;
    box-shadow:0 0 15px rgba(0,255,255,.15);
}

h2{
    color:#2dd4bf;
    margin-bottom:15px;
}

ul{
    margin-left:20px;
}

.code{
    background:#020617;
    padding:15px;
    border-radius:10px;
    overflow:auto;
    margin-top:15px;
}

pre{
    color:#7dd3fc;
}

canvas{
    margin-top:20px;
}

.flow{
    display:flex;
    justify-content:center;
    flex-wrap:wrap;
    gap:20px;
    margin-top:25px;
}

.box{
    background:#14b8a6;
    color:white;
    padding:15px 25px;
    border-radius:10px;
    font-weight:bold;
    animation:float 3s infinite;
}

@keyframes float{
    0%{transform:translateY(0)}
    50%{transform:translateY(-10px)}
    100%{transform:translateY(0)}
}

footer{
    text-align:center;
    padding:30px;
    background:#020617;
}
</style>

</head>

<body>

<header>
<h1>📚 Sistema de Boletim Escolar</h1>
<p>Projeto em Python com Modularização e Estruturas de Dados</p>
</header>

<section>

<div class="card">
<h2>📖 Sobre o Projeto</h2>

<p>
Este sistema foi desenvolvido em Python para realizar o cadastro de alunos,
armazenar notas, calcular médias, registrar frequência e exibir o resultado final.
</p>

<p>
O projeto utiliza:
</p>

<ul>
<li>Funções (Modularização)</li>
<li>Dicionários</li>
<li>Listas</li>
<li>Loops</li>
<li>Estruturas Condicionais</li>
<li>Manipulação de Dados</li>
</ul>

</div>

<div class="card">

<h2>⚙️ Fluxo do Sistema</h2>

<div class="flow">
<div class="box">Cadastrar Aluno</div>
<div class="box">Inserir Notas</div>
<div class="box">Calcular Média</div>
<div class="box">Registrar Frequência</div>
<div class="box">Exibir Resultado</div>
</div>

</div>

<div class="card">

<h2>🧩 Estrutura das Funções</h2>

<table width="100%" border="1" cellpadding="10">
<tr>
<th>Função</th>
<th>Responsabilidade</th>
</tr>

<tr>
<td>calcular_nota()</td>
<td>Calcula a média do aluno</td>
</tr>

<tr>
<td>calcular_frequencia()</td>
<td>Soma as presenças</td>
</tr>

<tr>
<td>cadastrar_aluno()</td>
<td>Recebe os dados do aluno</td>
</tr>

<tr>
<td>exibir_resultados()</td>
<td>Mostra o boletim final</td>
</tr>

</table>

</div>

<div class="card">

<h2>📊 Modularização do Projeto</h2>

<canvas id="modularizacao"></canvas>

</div>

<div class="card">

<h2>📈 Distribuição das Responsabilidades</h2>

<canvas id="responsabilidades"></canvas>

</div>

<div class="card">

<h2>💻 Exemplo de Estrutura de Dados</h2>

<div class="code">
<pre>
{
    "nome":"João",
    "boletim":{
        "Matemática":{
            "notas":[8,7,9],
            "media":8,
            "presenca":60
        }
    }
}
</pre>
</div>

</div>

<div class="card">

<h2>🚀 Tecnologias Utilizadas</h2>

<ul>
<li>Python 3</li>
<li>Funções</li>
<li>Dicionários</li>
<li>Listas</li>
<li>HTML5</li>
<li>CSS3</li>
<li>Chart.js</li>
</ul>

</div>

<div class="card">

<h2>🎯 Objetivos de Aprendizagem</h2>

<ul>
<li>Modularização de código</li>
<li>Estruturas de dados</li>
<li>Manipulação de listas</li>
<li>Uso de dicionários</li>
<li>Boas práticas de programação</li>
<li>Organização de sistemas</li>
</ul>

</div>

</section>

<footer>
Desenvolvido para estudo de Python e Programação Estruturada
</footer>

<script>

new Chart(
document.getElementById('modularizacao'),
{
type:'bar',
data:{
labels:[
'Calcular Nota',
'Frequência',
'Cadastro',
'Resultados'
],
datasets:[{
label:'Complexidade',
data:[20,15,40,25]
}]
},
options:{
responsive:true,
animation:{
duration:2500
}
}
}
);

new Chart(
document.getElementById('responsabilidades'),
{
type:'doughnut',
data:{
labels:[
'Entrada de Dados',
'Processamento',
'Validação',
'Saída'
],
datasets:[{
data:[40,30,10,20]
}]
},
options:{
responsive:true,
animation:{
animateRotate:true,
duration:3000
}
}
}
);

</script>

</body>
</html>
