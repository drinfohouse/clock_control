# DrinfoHouse: Clock Control
Aplicativo para limitação de clock de CPU.

## 🚀 1. Descrição
**Clock Control** é uma ferramenta de automação via Batch/PowerShell desenvolvida para técnicos e entusiastas que precisam de controle sobre a frequência térmica de processadores. 

O Windows, de forma nativa, não oferece um controle direto e simplificado sobre a frequência do processador. Embora o sistema gerencie o desempenho, ele prioriza a entrega de potência, o que pode resultar em altas temperaturas em ambientes de manutenção ou em notebooks com sistemas de arrefecimento limitados.

## 🛠️ 2. Funcionalidades Principais

- **Limitação de Clock**: Permite definir o teto de frequência entre 1000 MHz e 5000 MHz.


- **Reset**: O script contém a opção de RESET que remove todas as travas e restaura o desempenho máximo de fábrica do processador.

- **Auto-Elevação**: Sistema inteligente que detecta e auxilia na falta de privilégios de Administrador 

- **Error Handling**: identifica erros de digitação e auxilia na correção.

## 🛡️ 3. Vantagens de Controle de Clock
- **Térmica**: alto poder de redução de temperatura.

- **Longevidade de Hardware**: Diminui o estresse sobre os componentes eletrônicos e o sistema de arrefecimento (fans e dissipadores), especialmente em notebooks com projetos térmicos limitados.

- **Acústica**: tendencia de ambiente mais silencioso.

- **Vcore**: não demanda de alterações de alimentação do CPU, funcionamento "tal qual"

## 📋 4. Como Usar
- Baixe o arquivo clock_control.bat na aba Releases.
- Execute o arquivo no modo Administrado.
- Insira o valor desejado em MHz (Ex: 2500) ou 0 para resetar.
- Monitore a mudança em tempo real utilizando ferramentas como o Core Temp ou CPU-Z.

## 📊 5. Monitoramento
Para monitoramento de temperatura recomendamos Core Temp.
https://www.alcpu.com/CoreTemp/


## ⚖️ 6. Licença
MIT License
- Uso Comercial: O script pode ser utilizado em serviços técnicos e empresas de manutenção.
- Modificação: O código pode ser alterado e adaptado para necessidades específicas de bancada.
- Distribuição: Você pode compartilhar o software.

Importante: O software é fornecido "como está", **sem garantias de qualquer tipo**.

## 👨‍💻 7. Autor
**Daniel** *Proprietário da DrInfoHouse*

Especialista em manutenção de hardware e otimização de sistemas, focado em entregar soluções baseadas em dados reais e integridade de componentes.

- Site: https://sites.google.com/view/drinfohouse/home
- Youtube: https://www.youtube.com/@drinfohouse

Contato:
dr.ih@outlook.com
