O WSL não é utilizado em ambientes de produção, onde temos que rodar uma aplicação o tempo todo, já que o próprio Windows não é muito utilizado, e o WSL é uma ferramenta exclusiva do Windows. O Windows não é muito utilizado em servidores por alguns motivos, sendo os principais:

* A necessidade de uma licença paga por servidor, igual temos nos computadores pessoais, porém para o Windows Server;
* A instabilidade, principalmente nos sistemas que ficam ligados 24 horas por dia, onde vários pequenos serviços acabam acumulando erros e forçando uma reinicialização do servidor;
* As atualizações constantes que dependem de uma reinicialização do sistema para serem concluídas;
* Não ter o código aberto, impedindo que modificações legítimas sejam feitas para correção de erros, desativação de recursos ou melhorias de desempenho, atrapalhando e dificultando a execução de certas aplicações.

Com todas essas limitações, o WSL não é uma ferramenta muito comum para pessoas de DevOps, já que sua utilização em servidores não é recomendada e devemos sempre rodar e testar códigos com o ambiente mais próximo do real, porém ele acaba sendo muito popular entre pessoas que desenvolvem softwares, já que o WSL consegue rodar a maioria dos comandos padrão do Linux e é mais rápido e leve que uma máquina virtual, como as do VirtualBox.