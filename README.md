# 🗺️ Endereçamento IP da Rede Local - Minha Casa IoT

Este documento detalha o plano de endereçamento IP para os dispositivos conectados à rede local da sua casa inteligente. Uma organização clara dos IPs é fundamental para o gerenciamento, manutenção e identificação de cada componente do sistema IoT.

---

## 📋 Tabela de Dispositivos Conectados

A tabela abaixo lista os endereços IP atribuídos a cada dispositivo IoT e computador dentro da sua rede local (VLAN ou segmento de rede principal).

| Endereço IP     | Dispositivo       | Notas                                                                                                                                                                                                                                            |
| :-------------- | :---------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `192.168.1.1`   | Lâmpada           | Iluminação da Sala 1                                                                                                                                                                                                                     |
| `192.168.1.2`   | Lâmpada           | Iluminação da Sala 2                                                                                                                                                                                                                     |
| `192.168.1.3`   | Notebook          | Dispositivo de uso geral                                                                                                                                                                                                                 |
| `192.168.1.4`   | Lâmpada           | Iluminação da Cozinha 1                                                                                                                                                                                                                  |
| `192.168.1.5`   | Lâmpada           | Iluminação da Cozinha 2                                                                                                                                                                                                                  |
| `192.168.1.6`   | Lâmpada           | Iluminação do Quarto Principal 1                                                                                                                                                                                                         |
| `192.168.1.7`   | Lâmpada           | Iluminação do Quarto Principal 2                                                                                                                                                                                                         |
| `192.168.1.8`   | Lâmpada           | Iluminação do Banheiro Social 1                                                                                                                                                                                                          |
| `192.168.1.9`   | Lâmpada           | Iluminação do Banheiro Social 2                                                                                                                                                                                                          |
| `192.168.1.10`  | Lâmpada           | Iluminação da Garagem                                                                                                                                                                                                                    |
| `192.168.1.11`  | Lâmpada           | Iluminação Externa (Frente)                                                                                                                                                                                                              |
| `192.168.1.12`  | Lâmpada           | Iluminação Externa (Fundos)                                                                                                                                                                                                              |
| `192.168.1.13`  | Lâmpada           | Iluminação da Piscina                                                                                                                                                                                                                    |
| `192.168.1.14`  | Lâmpada           | Iluminação do Escritório 1                                                                                                                                                                                                               |
| `192.168.1.15`  | Lâmpada           | Iluminação do Escritório 2                                                                                                                                                                                                               |
| `192.168.1.16`  | Lâmpada           | Iluminação do Hall de Entrada                                                                                                                                                                                                            |
| `192.168.1.17`  | Alexa             | Assistente Virtual da Sala                                                                                                                                                                                                               |
| `192.168.1.18`  | Alexa             | Assistente Virtual do Quarto Principal                                                                                                                                                                                                   |
| `192.168.1.19`  | Aquecedor         | Aquecedor de Água                                                                                                                                                                                                                        |
| `192.168.1.20`  | TV                | TV da Sala                                                                                                                                                                                                                               |
| `192.168.1.21`  | TV                | TV do Quarto Principal                                                                                                                                                                                                                   |
| `192.168.1.22`  | TV                | TV do Quarto de Hóspedes                                                                                                                                                                                                                 |
| `192.168.1.23`  | Câmera            | Câmera de Segurança - Entrada Principal                                                                                                                                                                                                  |
| `192.168.1.24`  | Câmera            | Câmera de Segurança - Garagem                                                                                                                                                                                                            |
| `192.168.1.25`  | Câmera            | Câmera de Segurança - Quintal (Frente)                                                                                                                                                                                                   |
| `192.168.1.26`  | Câmera            | Câmera de Segurança - Quintal (Fundos)                                                                                                                                                                                                   |
| `192.168.1.27`  | Câmera            | Câmera de Segurança - Corredor Interno                                                                                                                                                                                                   |
| `192.168.1.28`  | Câmera            | Câmera de Segurança - Área da Piscina                                                                                                                                                                                                    |
| `192.168.1.29`  | Câmera            | Câmera de Segurança - Portão Lateral                                                                                                                                                                                                     |
| `192.168.1.30`  | Persiana          | Persiana da Sala de Estar                                                                                                                                                                                                                |
| `192.168.1.31`  | Persiana          | Persiana do Quarto Principal                                                                                                                                                                                                             |
| `192.168.1.32`  | Persiana          | Persiana do Escritório                                                                                                                                                                                                                   |
| `192.168.1.33`  | Ar-condicionado   | Ar Condicionado da Sala                                                                                                                                                                                                                  |
| `192.168.1.34`  | Ar-condicionado   | Ar Condicionado do Quarto Principal                                                                                                                                                                                                      |
| `192.168.1.35`  | Ar-condicionado   | Ar Condicionado do Quarto de Hóspedes                                                                                                                                                                                                    |
| `192.168.1.36`  | Tablet            | Dispositivo de controle central                                                                                                                                                                                                          |
| `192.168.1.37`  | Fogão            | Dispositivo de controle central                                                                                                                                                                                                          |
| `192.168.1.38`  | Chuveiro            | Dispositivo de controle central                                                                                                                                                                                                          |
| `192.168.1.39`  | Fechadura            | Dispositivo de controle central                                                                                                                                                                                                          |

---

## 🌐 Informações da Rede Local

* **Range da Rede Local:** `192.168.1.0/26`
* **Máscara de Sub-rede:** `255.255.255.192`
* **Endereço de Rede:** `192.168.1.0`
* **Endereço de Broadcast:** `192.168.1.63`
* **IPs Utilizáveis:** `192.168.1.1` a `192.168.1.62`
* **Total de IPs Disponíveis:** 62 hosts

Esta configuração de sub-rede (`/26`) fornece uma quantidade adequada de endereços IP para os dispositivos da casa inteligente, permitindo expansões futuras sem a necessidade de reconfiguração imediata da rede.

---

## 💡 Boas Práticas

* **IPs Estáticos/Reservados:** Para dispositivos críticos (Home Assistant, câmeras, painéis de controle, roteadores), é recomendado configurar IPs estáticos ou reservas DHCP para garantir que seus endereços não mudem.
* **Documentação:** Mantenha esta tabela atualizada sempre que um novo dispositivo for adicionado ou removido da rede.
* **Segurança:** Considere implementar segmentação de rede (VLANs) para isolar dispositivos IoT de outros segmentos da rede, aumentando a segurança.

---

## 🧑‍💻 Desenvolvido por

* **José Marco**
* **Helloysa Rocha**
* **Gabrielly Dias**
* **HAGMA**
