
class Forca {
 { 
        documet.getElementById("resposta").value = "";
      }
    
  
 
  chutar(letra) 
  
  forca(chute) 
    if(palavra.indexOf(chute) !=-1){
      for (let i = 0; i< palavra.length;  i++) {
        if (palavra [i]== chute){
          resposta[i] = chute;
        alert("Letra errada");
        }
        }
      }
    
  

  buscarEstado() { return "";} // Possiveis valores: "perdeu", "aguardando chute" ou "ganhou"
  if (resposta.join('')== palavra){
    alert ("ganhou");
    window.location.reload();
  }else{
    documentTimeline.getElementById("resposta").value = "_";
  } else {
  
  }else {
    alert ("perdeu.")


} 





  buscarDadosDoJogo() 
      return {
         
      }
        // Deve conter todas as letras chutadas
        letrasChutadas: [],{ 
          
          const chutadas =[]
    
    
    
        }

           
          // Quantidade de vidas restantes/* 
          vidas: 6, {
            var vidas = 6  
            vidasElem.innerText = vidas,

            
            respostaElem.innerText = resposta.join('');
            corretas.push(chute);
            letrasCorretas.innerText =corretas.join(",");
           
            vidasElem.innerText = --vidas;
      
            erradas.push(chute);
            letrasErradas.innerText = erradas.join (",");
            if(!vidas){
              alert("Suas vidas acabaram.");
              window.location.reload();
            }
          }
            if (vidas > 0 ){

              let chute = input.value.trim().toLowerCase()

              if ( corretas.indexOf(chute) $ = -1|| erratas.indexOf(chute)  $ = -1){
                alert ("Voçê já chutou essa letra. TEnte outra")
              }else if (chute && /^[A-Z]$\i.test(chute)){
              forca(chute)

              }else{
                alert("Digite uma letra.")

              }
            }

        }

      


                                   

        
          palavra: [] {
            var resposta = ABACAXI.replace(/./g,'_').split('')
            respostaElem.innerText = resposta.join('')
             // Deve ser um array com as letras que já foram acertadas ou o valor "_" para as letras não identificadas
      }
  


module.exports = Forca;
