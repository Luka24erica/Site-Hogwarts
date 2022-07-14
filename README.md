# Site-Hogwarts
<!DOCTYPEhtml >
< html  lang =" en " >
< cabeça >
    < meta  charset =" UTF-8 " >
    < meta  http-equiv = " Conteúdo compatível com X-UA " =" IE=edge " >
    < meta  name =" viewport " content =" largura=largura do dispositivo, escala inicial=1.0 " >
    < link  rel =" folha de estilo " href =" style.css " >
    < title > Casas de Hogwarts </ title >
    < link  rel =" ícone de atalho " href =" imagens/favicon.png " type =" imagem/png " >
</ cabeça >
< corpo >
    < classe div  =" mae " >
        <!--cabecalho-->
        < classe div  =" cabeçalho " >
            <a href="#"> _  _ _ _ _
                < img  id =" logo " src =" imagens/logo.png " >
            </a> _ _
        </ div >
    </ div >
    < classe de navegação  =" menu " >
        < a  class =" menu menu--option " href =" jkrowlin.html " > JK Rowlin </ a >
        < a  class =" menu menu-option " href =" personagemfavorito.html " > Personagem Favorito </ a >
        < a  class =" menu menu menu--option " href =" curiosidades.html " > curiosidades </ a >
    </ nav >

    < div  class =" mae " id =" conteudo " >
        < section  class =" casas " >
            < div  class =" casas-conteudo " >
                < a  href =" lufalufa.html " >
                < img  class =" casa-logo " src =" imagens/hufflepuff.png " >
                < p  class =" casas-nome " > Lufa-Lufa </ p >
            </a> _ _
            </ div >
            < div  class =" casas-conteudo " >
                < a  href =" sonserina.html " >
                < img  class =" casa-logo " src =" imagens/slytherin.png " >
                < p  class =" casas-nome " > Sonserina </ p >
            </a> _ _
            </ div >
            < div  class =" casas-conteudo " >
                < a  href =" grifinoria.html " >
                < img  class =" casa-logo " src =" imagens/gryffindor.png " >
                < p  class =" casas-nome " > Grifinória </ p >
            </a> _ _
            </ div >
            < div  class =" casas-conteudo " >
                < a  href =" corvinal.html " >
                < img  class =" casa-logo " src =" imagens/ravenclaw.png " >
                < p  class =" casas-nome " > Corvinal </ p >
            </a> _ _
            </ div >
        </ seção >

    </ div >
    </ div >
</ corpo >
</ html >

@font-face {
    font-family :  'Harry' ;
    src :  url (fontes/WizardWorldSimplified-Kxr7.ttf);
}

@font-face {
    font-family :  'Casas' ;
    src :  url (fontes/parry-hotter.regular.ttf);
}

@media ( largura máxima :  400 px ) {
    . cardápio {
        exibição : flexível;
        flex-direction : coluna;
    }

    . casas {
        exibição : flexível;
        flex-direction : coluna;
        margem superior :  2 % ;
        align-content : espaço entre;
        topo acolchoado :  3 % ;
    }
}

corpo {
    background-image :  url ( "imagens/background2.jpeg" );
    tamanho do fundo : capa;
    altura máxima :  100 % ;
    tamanho da fonte :  20 px ;
}

. mãe {
    cor de fundo :  rgba ( 187 ,  187 ,  187 ,  0,199 );
}

img {
    largura :  100 % ;
}

. cabeçalho {
    exibição : flexível;
    justificar-conteúdo : centro;
    preenchimento :  0,5 % ;
}

. cardápio {
    preenchimento :  1 % ;
    text-align : centro;
    box-shadow :  2 px  2 px  8 px preto;
    cor de fundo :  rgba ( 190 ,  186 ,  186 ,  0,199 );
    font-family :  "Harry" ;
    decoração de texto : nenhuma;
    cor : branco;
    tamanho da fonte :  20 px ;
}

. menu--opção {
    transição :  0,3 s de facilidade;
    borda superior :  4 px sólido rgba ( 187 ,  187 ,  187 ,  0,199 );
    border-bottom :  4 px sólido rgba ( 187 ,  187 ,  187 ,  0,199 );
    preenchimento :  1 %  0 ;
    margem :  0px 2 % ; _ 
    text-shadow :  2 px  2 px preto;
    tamanho da fonte :  1,2 em ;
}

. opção de menu : hover {
    border-top :  branco sólido de 4 px ;
    border-bottom :  branco sólido de 4 px ;
    preenchimento :  0,4 %  0 ;
    cor de fundo :  rgb ( 14 ,  94 ,  7 );
}

# conteudo {
    margem superior :  2 % ;
    preenchimento :  30px ; _
}

. casas {
    exibição : flexível;
    margem superior :  2 % ;
    align-content : espaço entre;
    topo acolchoado :  3 % ;
}

. casas-logo {
    altura :  200px ; _
    largura máxima :  200 px ;

}

. casas  img {
    largura :  200px ; _
    altura :  230px ; _
}

. casas-conteudo {
    margem : automático;
    text-align : centro;
}

. casas-nome {
    font-family :  "Casas" ;
    cor : branco;
    tamanho da fonte :  1,2 em ;
    text-shadow :  2 px  2 px preto;
}

/*Estilo da página formulario */

# pf-conteudo {
    exibição : flexível;
    cor : branco;
    font-family :  "Harry" ;
    margem superior :  20 px ;
}

. formulário {
    text-shadow :  2 px  2 px preto;
    preenchimento :  10px ; _
    largura :  100 % ;
    
}

. entrada de formulário  [ tipo = "texto" ] {
    altura da linha :  30 px ;
    largura :  300px ; _
    margem :  10px ; _
  
}

. rótulo do formulário  {
    margem :  10px ; _
}

. input-opcoes {
    alinhamento vertical : meio;
    margem :  10px ; _
    preenchimento :  10px ; _
}

. botao {
    preenchimento :  5px 15px ; _  _
    cor de fundo : branco;
    borda : nenhuma;
    cursor : ponteiro;
    raio da borda :  5 px ;
    tamanho da fonte :  15 px ;
    font-family :  "Harry" ;
    box-shadow :  2 px  2 px preto;
}

. saída {
    align-self : centro;
    text-align : centro;
    align-items : centro;
    largura :  100 % ;
    text-shadow :  2 px  2 px preto;
}

. texto de entrada {
    exibição : flexível;
    flex-flow : quebra de coluna;
    justificar-conteúdo : flex-start;
}

# conteudo-jk {
    cor de fundo :  rgba ( 187 ,  187 ,  187 ,  0,199 );
    exibição : flexível;
}

#fotosimg  { _ _
    largura :  250px ; _
    preenchimento :  30px ; _
}

# fotos  p {
    font-family :  'Casas' ;
    tamanho da fonte :  30 px ;
    cor : branco;
    text-align : centro;
}

. legenda {
    font-family :  'WizardWorld' ;
    cor : branco;
    tamanho da fonte :  25px ;
    text-shadow :  2 px  2 px preto;
}

# bio-jk {
    tamanho da fonte :  20 px ;
    cor : branco;
    text-shadow :  2 px  2 px preto;
    text-justify : inter-palavra;
    preenchimento :  20px ; _
}

. imagem emblemática  {
    largura máxima :  300 px ;
    preenchimento :  30px ; _
}

. conteudo-texto {
    preenchimento :  30px ; _
    tamanho da fonte :  20 px ;
    text-align : justificar;
    cor : branco;
}

. frase-casa {
    align-self : centro;
    largura :  100 % ;
    tamanho da fonte :  25px ;
    cor : branco;
    estilo da fonte : itálico;
}
