# filosofem - ghost client 

filosofem foi um projeto de um final de semana, desenvolvido para alterar somente os fields de uma maquina virtual java (mc)</br>
a ideia principal e largar o metodos tradicionais de buscar mappings atraves do jni.h para altera-los em runtime (o que trazia muitos problemas de crashes e de memory leaks caso os mappings estivessem incorretos) para um metodo de alteração direta dos dicionários que ficam guardados na memoria da maquina (jre 8) resolvendo diretamente o erro de alterar mappings que não existem e de memory leaks do programa.</br></br>

o projeto compila para 86x em .exe sem a necessidade de injeção de dll's</br>
todo...
