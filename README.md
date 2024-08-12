# styles.css
body {
    color: rgb(170, 155, 224);
    background: black;
    margin: 0px;
    font-family: "Chakra Petch", sans-serif;
    margin-bottom: 100px;
}

header {
    border-bottom: solid 2px rgb(76, 78, 80);
    padding: 50px;
    font-size: 32px;
    color: rgb(0, 2, 4);
}

.chamada {
    background: rgb(129, 3, 3);
    padding-bottom: 70px;
    padding-top: 90px;
    display: flex;
    justify-content: center;
}

.chamada-texto {
    margin-right: 15%;
}

h1 {
    font-size: 40px;
}

p {
    font-size: 20px;
}

.categoria-videos {
    display: flex;
    overflow-x: auto;
    gap: 10px;
}

.categoria {
    padding-left: 20px;
    padding-right: 20px;
    margin-top: 55px;
}

.categoria-videos img {
    opacity: 0.5;
    height: 220px;
}

.categoria-videos img:hover {
    opacity: 1.0;
    border: 3px solid rgba(15, 225, 50, 0.526);
}

.categoria h2 {
    color: rgb(2, 8, 89);
}
