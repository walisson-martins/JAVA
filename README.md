Projeto com JSF 1 e migrando para o JSF 2 -> Projeto Livraria

Também verifique os sites e showcases das extensões: 
primefaces: http://primefaces.org/

richfaces: http://richfaces.org/

icefaces: http://icefaces.org/

Download do Apache tomcat --> http://tomcat.apache.org/download-70.cgi container servelet

No Eclipse vá em New > Project e selecione Dynamic Web Project e clique Next;

Coloque o nome do projeto como jsf-livraria, selecione como Target Runtime a versão do Tomcat que acabamos de configurar e na combobox Configuration selecione JavaServer Faces v2.0 Project. Clique em Next

Nas duas próximas telas (Source folders on build path e Configure web module settings, clique em Next só para confirmar as opções;

Na tela JSF Capabilities, selecione Disable Library Configuration no combobox do JSF Implementation Library e se na seção URL Mapping Patterns estiver /faces/* (ou algo diferente de *.xhtml), clique em remover (remova todos) e adicione (ou mantenha) somente *.xhtml. Clique em Finish;

Pronto, seu projeto já está criado com suporte ao JSF2. Se você olhar na pasta WebContent\WEB-INF encontrará os arquivos faces-config.xml e web.xml e dentro deles as configurações do namespace do JSF e da Servlet que controla a execução do JSF no Container.

Cole aqui o conteúdo dos arquivos faces-config.xml e web.xml, respectivamente:

Tem que adicionar a bibliteca do Primefaces as bibliotecas em nosso computador, copie o arquivo javax.faces-2.1.x.jar para a pasta WebContent/WEB-INF/lib do seu projeto (jsf-livraria).
