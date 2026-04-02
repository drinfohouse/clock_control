<p align="center">
  <img src="https://raw.githubusercontent.com/drinfohouse/clock_control/main/clock_control_print_screen.png" alt="Interface do Clock Control" width="500">
</p>

### DrInfoHouse: Clock Control
#### Automação para Limitação Térmica e Eficiência de Processadores

O **Clock Control** é uma ferramenta de automação desenvolvida via Batch/PowerShell para técnicos e entusiastas que necessitam de controle rigoroso sobre a frequência de operação de processadores AMD e INTEL.

#### 🚀 1. Por que usar o Clock Control?
O Windows, de forma nativa, prioriza a entrega máxima de potência, o que frequentemente resulta em altas temperaturas e ruído excessivo, especialmente em notebooks com sistemas de arrefecimento limitados. Esta ferramenta oferece um controle direto e simplificado, permitindo estabilizar o sistema sem a necessidade de configurações complexas na BIOS.

#### 🛠️ 2. Funcionalidades Principais
* **Limitação de Clock:** Permite definir o teto de frequência entre 1000 MHz e 5000 MHz.
* **Suporte a Arquiteturas Híbridas:** Identifica e atua sobre núcleos de Performance (P-Cores) e Eficiência (E-Cores) em processadores modernos.
* **Auto-Elevação:** Sistema inteligente que detecta e solicita privilégios de Administrador automaticamente.
* **Modo Reset:** Comando simplificado (valor 0) para restaurar instantaneamente as configurações originais de fábrica.
* **Tratamento de Erros:** Identifica falhas de digitação e auxilia na correção imediata.

#### 🛡️ 3. Benefícios Práticos
* **Gestão Térmica:** Redução drástica de temperatura em ambientes de alta carga.
* **Longevidade de Hardware:** Diminuição do estresse térmico sobre componentes sensíveis e ventoinhas.
* **Conforto Acústico:** Redução do ruído dos fans devido à menor demanda de resfriamento.
* **Eficiência Energética:** Otimização do consumo sem necessidade de alterar tensões (Vcore) manualmente.

#### 📥 4. Como Baixar
O aplicativo pode ser baixado diretamente na aba [**Releases**](https://github.com/drinfohouse/clock_control/releases) deste repositório. Procure pelo arquivo `clock_control.bat` na versão mais recente.

#### 📋 5. Como Operar
1. Após baixar, execute o arquivo como **Administrador**.
2. Insira a frequência desejada em MHz (Ex: 2500 para 2.5GHz) ou 0 para Reset.
3. Monitore a alteração em tempo real com ferramentas como **Core Temp** ou **CPU-Z**.

#### Sobre o Autor
**Daniel** é o fundador da **DrInfoHouse** e especialista em hardware. Com mais de 20 anos de experiência, desenvolve ferramentas e materiais didáticos focados na integridade de hardware e otimização de performance baseada em dados reais.

#### Licença e Uso
Este software é distribuído sob a **Licença MIT**, permitindo uso comercial, modificação e redistribuição, desde que mantidos os créditos de autoria.

---
<p align="center">
  <a href="https://github.com/drinfohouse/empresa">🏠 Página Principal DrInfoHouse</a> | 
  <a href="https://youtube.com/@drinfohouse">🎥 Canal Técnico no YouTube</a>
</p>
