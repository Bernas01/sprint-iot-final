# Sprint IoT Final

## Descrição
Este repositório contém o projeto **Sprint IoT Final**, desenvolvido para monitoramento e controle de dispositivos IoT utilizando ESP32. O projeto implementa sensores para capturar dados ambientais e aciona dispositivos com base em lógicas predefinidas.

## Tecnologias Utilizadas
- **ESP32**: Microcontrolador utilizado para captura e processamento de dados.
- **Arduino IDE**: Plataforma de desenvolvimento utilizada para programar o ESP32.
- **MQTT**: Protocolo de comunicação utilizado para transmissão de dados.
- **Banco de Dados**: Armazena os dados coletados pelos sensores.
- **Dashboard Web**: Interface gráfica para visualização dos dados coletados.

## Funcionalidades
- Leitura de sensores de temperatura e umidade.
- Monitoramento remoto via MQTT.
- Controle de dispositivos (LEDs, motores, etc.).
- Registro e armazenamento de dados em um banco de dados.
- Exibição dos dados em um dashboard web.

## Como Configurar
1. Clone este repositório:
   ```bash
   git clone https://github.com/Bernas01/sprint-iot-final.git
   ```
2. Instale a **Arduino IDE** e configure a placa ESP32.
3. Instale as bibliotecas necessárias na Arduino IDE.
4. Conecte o ESP32 ao computador e carregue o código.
5. Configure o broker MQTT e o banco de dados.
6. Inicie o dashboard web para visualização dos dados.

## Estrutura do Projeto
```
/
├── firmware/        # Código para o ESP32
├── dashboard/       # Interface web para visualização dos dados
├── database/        # Scripts de configuração do banco de dados
├── docs/            # Documentação do projeto
└── README.md        # Este arquivo
```

## Contribuição
Contribuições são bem-vindas! Para contribuir, siga os passos:
1. Fork este repositório.
2. Crie um branch para suas alterações: `git checkout -b minha-feature`.
3. Commit suas alterações: `git commit -m 'Adiciona nova funcionalidade'`.
4. Envie para o repositório remoto: `git push origin minha-feature`.
5. Abra um Pull Request.

## Autor
Desenvolvido por **Felipe Bernardes de Almeida**.

## Licença
Este projeto está licenciado sob a [MIT License](LICENSE).

