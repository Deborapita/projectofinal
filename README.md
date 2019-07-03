# Portfólio | Débora Pita 
Para este projecto de programação decidi desenvolver um pequeno portfólio/cv, que tem com principal objectivo divulgar informação e trabalho com um visual apelativo e clean com pequenas interações nos cards onde se situam as áreas de trabalho todas identificadas com iconografia e pequenos textos explicativos, e nos botões para passar a ideia de movimento. Em todo o site contemos algumas secções como area de apresentação (hero), cv, areas de trabalho, ver projecto e por final contactos.

## Tecnologias Utilizadas

### HTML
Foi utilizado para elaborar a estrutra da página. Usei muitos HTMLelement ex. header, main, footer, div, section, figure. Porque facilita na leitura do codigo e dos motores de busca

### SCSS
Utilizei o SCSS para estilizar o a página.

1. Variaveis
     - Nas cores principais, porque são as cores base e para evitar colocar sempre os hexa (no qual posso errar no valor)
     
2. Nesting
     - Facilitou bastante, porque não tive de repetir vezes sem conta os selectores
     - Ajudou na organização do código

3. Mixin
     - Para conseguir centrar elementos com função true, false
     - Usei tambem para o responsive através de includes, assim não tive de colocar breakpoints e repetir codigo
     
### Responsive
Para o responsive defini 3 larguras e apliquei através de includes nos elementos especificos caso fosse necessario ajustar alguma coisa:
  $desktop: "(min-width: 1024px)";
  $tablet: "(min-width: 768px) and (max-width: 1023px)";
  $mobile: "(max-width: 767px)";
  
### Jekyll
Foi a parte mais complicada do projecto, porque integrar os varios modulos(ex. header, main, footer) da estrutura não estavam a funcionar com o CSS aplicado.

### Flexbox
Utilizei para alinhar as varias divs e estruturar os cards/sections. Usei porque facilita muito no responsive e quando se escala o viewport

### Form
Coloquei na area de contacto para as pessoas conseguirem comunicar comigo (usando metodo GET)

### Animations
Usei nas cards atraves do translade ela move com hover e nos botões
