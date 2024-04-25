![image](https://github.com/Alexandre-Konrath/teste-grid/assets/160286787/1eb598a9-afe1-4c40-91ee-9e0e18698611)

Mesmo preferindo o display: flex; aprendi diversas coisas muito interessantes com o display: grid;.  
Coisas que o flex, seriam um pouco mais complexas de se fazer, e o grid deixa mais fácil. Vi que criar colunas e linhas nunca foi tão fácil, usando por exemplo.  
ㅤdisplay: grid;  
ㅤgrid-template-columns: auto auto auto;  
ㅤgrid-template-rows: auto auto auto auto;  
ou fazendo deste modo, colocando classes no objeto que deseja, e você literalmente pode colocá-lo em qualquer lugar.  
ㅤdisplay: grid;  
ㅤgrid-template-areas:  
ㅤㅤ"gato9 gato12 gato10"  
ㅤㅤ"gato15 gato14 gato13"  
ㅤㅤ"gato16 gato17 gato11";  
ㅤmargin: 10px;

.gato9 { grid-area: gato9; }  
.gato10 { grid-area: gato10; }
