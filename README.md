* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Lato", sans-serif;
  }
  
  body {
    background-color: #090e22;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    color: #fff;
  }
  
  .hide {
    display: none  !important;
  }
  
  .container {
    min-width: 400px;
    min-height: 400px;
    background-color: #1d1e33;
    padding: 2rem;
  }
  
  /* CADASTRO ALUNO */
  #cadastro-container h2 {
    text-align: center;
    margin-bottom: 2rem;
  }
  
  .cad-inputs {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
  }

.cad-control {
    display: flex;
    flex: 1;
    flex-direction: column;
    margin-bottom: 1rem;
    
}

.cad-control label {
    font-weight: bold;
    margin-bottom: 0.6rem;
   color: #ccc;  
}

.cad-control input{
    padding: 1rem 0.5rem;

} 

.action-control{
    display: flex;
    justify-content: space-between;
    margin-top: 2rem;
    gap: 1rem;

}

button {
    text-transform: uppercase;
    padding: 1rem 1.5rem;
    background-color: tomato;
    border: none;
    color:#fff;
    cursor: pointer;
    opacity: 0.9;
    flex: 1; 

}

#del-btn {
  background-color: #444;
}

#Dados-container {
    text-align: center;
}

#SingUp {
    font-size: 1.4rem;
    color: #ccc;

}

#Dados-container h3 {
    margin-bottom: 1rem;
    color: #dfdfdf;

}

#Dados-conatiner {
    display: flex;
    flex-direction: column;
}
