   background: black;
    margin: 0px;
    font-family: "Chakra Petch", sans-serif;
@Tecnologiasonia
Tecnologiasonia on Aug 17
Captura de tela 2024-05-18 110041
(https://github.com/user-attachments/assets/20e09f1d-9a78-4966-a42f-64662ae4907d)

    margin-bottom: 100px;
}

header {
@@ -32,10 +33,6 @@ p {
    font-size: 20px;
}

img {
    height: 200px;
}

.categoria-videos {
    display: flex;
    overflow-x: auto;
@@ -45,4 +42,19 @@ img {
.categoria {
    padding-left: 20px;
    padding-right: 20px;
    margin-top: 50px;
}

.categoria-videos img {
    opacity: 0.5;
    height: 200px;
}

.categoria-videos img:hover {
    opacity: 1.0;
    border: 3px solid green;
}

.categoria h2 {
    color: rgb(42, 122, 228);
}
