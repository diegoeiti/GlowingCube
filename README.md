# GlowingCube

🚀 Demonstração

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Glowing Cube</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="cube">
        <div class="top"></div>
        <div>
            <span style="--i:0;"></span>
            <span style="--i:1;"></span>
            <span style="--i:2;"></span>
            <span style="--i:3;"></span>
        </div>
    </div>
</body>
</html>


🎯 Como o Cubo Gira - Explicação Técnica

📐 Estrutura 3D com CSS

.cube {
    transform-style: preserve-3d;
    transform: rotateX(-30deg);
    animation: animate 4s linear infinite;
}

![Demonstração do Projeto](assets/images/cubo.gif)
