# teste_bry
Teste para vaga de estágio em BRT Tecnologia
Foi utilizado visual code
Foi feito clone do git vcpkg, na pasta "C:\Dev"
Foi instalado o openSSL utilizando o vcpkg
Identificação dos erros aparentes no código
Adicionado a pasta vcpkg nas propriedades do projeto, na aba C/C++ no campo "Diretório de Inclusões Adicionais": 
"C:\Dev\vcpkg\packages\openssl_x64-windows\include;C:\Dev\vcpkg\installed\x64-windows\include;%(AdditionalIncludeDirectories)"
Foi incluido o certificado na pasta "C:\Dev\ac_raiz_bry_v3.crt"
Foi adicionado o "Argumentos do Comando", indicando a pasta e o certificado acima
