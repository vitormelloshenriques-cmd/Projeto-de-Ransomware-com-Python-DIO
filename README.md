🛡️ Entendendo um Ransomware na Prática com Python
Projeto desenvolvido como parte do Santander Bootcamp de Cibersegurança oferecido pela DIO em parceria com o Santander Brasil.

🎯 Sobre o Projeto
Este projeto tem como objetivo demonstrar, em um ambiente controlado e educacional, o funcionamento lógico por trás de um ataque de Ransomware utilizando a linguagem Python.

Através da implementação de scripts de criptografia e descriptografia de arquivos, é possível compreender os vetores de ataque comuns e a importância de medidas robustas de prevenção, detecção e resposta a incidentes na área de segurança da informação.

⚙️ Tecnologias e Bibliotecas Utilizadas
Python 3.x

Biblioteca pyaes (para manipulação e criptografia AES de arquivos)

Biblioteca os (para interação com o sistema de arquivos e diretórios)

📂 Estrutura do Repositório
Plaintext
├── encrypter.py    # Script responsável por isolar e criptografar o arquivo-alvo
├── decrypter.py    # Script responsável por reverter a criptografia usando a chave correta
└── README.md       # Documentação detalhada do projeto
💻 Como Funciona o Código
1. Criptografia (encrypter.py)
O script localiza um arquivo específico no sistema, lê o seu conteúdo original, aplica um algoritmo de criptografia simétrica utilizando uma chave predefinida e sobrescreve o arquivo original com os dados criptografados, alterando sua extensão para sinalizar o bloqueio.

2. Descriptografia (decrypter.py)
Para fins de testes e validação do laboratório, o script de descriptografia utiliza a mesma chave secreta para reverter o processo matemático aplicado pelo encrypter.py, restaurando o arquivo ao seu estado original e legível.

⚠️ Aviso Legal (Legal Disclaimer)
Este projeto foi desenvolvido estritamente para fins educacionais e de pesquisa em laboratório isolado. O uso de técnicas de criptografia maliciosa contra sistemas ou dados sem autorização prévia e explícita constitui crime cibernético.

👨‍💻 Autor
Desenvolvido por Vitor Mello Henriques Barreto.
