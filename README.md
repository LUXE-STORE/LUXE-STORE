/* styles.css */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    text-align: center;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
}

header h1 {
    margin: 0;
    font-size: 2em;
}

header p {
    margin: 5px 0;
    font-size: 1.2em;
}

#products {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    padding: 20px;
}

.product {
    width: 45%;
    margin: 10px;
    text-align: center;
    background-color: #fff;
    padding: 15px;
    border-radius: 5px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.product img {
    width: 100%;
    height: auto;
    border-radius: 5px;
}

.product h3 {
    font-size: 1.2em;
    margin: 10px 0;
}

.product p {
    font-size: 1em;
    color: #555;
}

.product button {
    background-color: #333;
    color: #fff;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    text-align: center;
}

.product button:hover {
    background-color: #444;
}
