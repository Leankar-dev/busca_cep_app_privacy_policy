# Politica de Privacidade - BuscaCep

## Idiomas / Languages / Idiomas

- [Portugues (PT-BR)](#portugues)
- [English](#english)
- [Espanol](#espanol)

---

<a name="portugues"></a>
# Portugues (PT-BR)

# Politica de Privacidade - BuscaCep

**Ultima atualizacao:** 08 de fevereiro de 2026

**Desenvolvedor:** leankar.dev
**Contato:** [www.leankar.dev](https://www.leankar.dev)
**Aplicativo:** BuscaCep
**Pacote:** leankar.dev.busca_cep_app

---

## 1. Introducao

Esta Politica de Privacidade descreve como o aplicativo **BuscaCep** ("nos", "nosso" ou "Aplicativo") coleta, utiliza, armazena e protege as informacoes dos usuarios ("voce" ou "usuario"). Nosso compromisso e com a transparencia e a protecao da sua privacidade.

Ao utilizar o BuscaCep, voce concorda com as praticas descritas nesta politica. Caso nao concorde com os termos aqui apresentados, recomendamos que nao utilize o Aplicativo.

---

## 2. Informacoes que Coletamos

### 2.1 Dados Pessoais

O BuscaCep **NAO coleta, armazena ou processa dados pessoais** de nenhuma natureza, incluindo, mas nao se limitando a:

- Nome, e-mail ou telefone
- Documentos de identificacao (CPF, RG, BI, NIF, etc.)
- Dados de localizacao (GPS)
- Dados biometricos
- Informacoes de contatos do dispositivo
- Fotos, videos ou arquivos do dispositivo
- Identificadores unicos de publicidade

### 2.2 Dados de Uso

O Aplicativo **NAO coleta dados de uso**, tais como:

- Historico de buscas realizadas
- Frequencia de uso do aplicativo
- Tempo de permanencia em telas
- Eventos de interacao (cliques, toques, navegacao)
- Dados de sessao

### 2.3 Dados Transmitidos a Terceiros

Durante o funcionamento normal do Aplicativo, os seguintes dados sao transmitidos **exclusivamente** para a API publica ViaCEP (`https://viacep.com.br/ws`):

| Tipo de Busca | Dados Transmitidos | Finalidade |
|---|---|---|
| Busca por CEP | Numero do CEP (8 digitos) | Consultar o endereco correspondente |
| Busca por Endereco | UF, cidade e logradouro | Consultar CEPs correspondentes |

**Importante:** Esses dados (CEPs e enderecos) sao informacoes de natureza publica e **nao constituem dados pessoais**. A transmissao e feita exclusivamente via protocolo **HTTPS** (criptografado).

### 2.4 Dados Coletados Automaticamente

O Aplicativo **NAO coleta automaticamente** nenhum tipo de dado, incluindo:

- Endereco IP (nao registrado pelo app; pode ser registrado pelo servidor da API ViaCEP conforme politica propria)
- Tipo de dispositivo ou sistema operacional
- Identificadores de dispositivo (IMEI, Android ID, etc.)
- Dados de cookies ou tecnologias de rastreamento
- Dados de diagnostico ou crash reports

---

## 3. Como Utilizamos as Informacoes

O BuscaCep utiliza as informacoes digitadas pelo usuario **unicamente** para:

- **Consultar enderecos**: Enviar o CEP ou endereco a API ViaCEP e exibir o resultado na tela
- **Exibir resultados**: Apresentar os dados de endereco retornados pela API ao usuario

**Nao utilizamos informacoes para:**

- Criar perfis de usuario
- Realizar publicidade direcionada
- Enviar notificacoes push ou e-mails
- Analisar comportamento de uso
- Comercializar ou compartilhar dados com terceiros
- Treinar modelos de inteligencia artificial

---

## 4. Armazenamento de Dados

### 4.1 Armazenamento Local

O BuscaCep **NAO armazena dados localmente** no dispositivo do usuario. Nao utilizamos:

- Banco de dados local (SQLite, Hive, Isar, etc.)
- SharedPreferences ou armazenamento chave-valor
- Cache em disco
- Arquivos no sistema de arquivos do dispositivo

### 4.2 Dados em Memoria

Os dados de busca e resultados sao mantidos **exclusivamente na memoria RAM** durante o uso ativo do Aplicativo. Ao fechar o app, trocar de aba de busca ou limpar os campos, **todos os dados sao descartados imediata e permanentemente**.

### 4.3 Armazenamento em Servidores

O BuscaCep **NAO possui servidores proprios** e **NAO armazena dados em nuvem**. Nao utilizamos:

- Firebase, AWS, Azure ou qualquer servico de nuvem
- Bancos de dados remotos
- Servicos de armazenamento de arquivos

---

## 5. Compartilhamento de Dados com Terceiros

### 5.1 Servicos de Terceiros Utilizados

O Aplicativo utiliza **um unico servico externo**:

| Servico | Provedor | Finalidade | Dados Compartilhados |
|---|---|---|---|
| API ViaCEP | viacep.com.br | Consulta de CEPs brasileiros | CEP ou endereco digitado |

A API ViaCEP e um servico **publico e gratuito** do governo brasileiro para consulta de codigos postais. Recomendamos que o usuario consulte a politica de privacidade do ViaCEP em [https://viacep.com.br](https://viacep.com.br) para informacoes sobre como eles tratam os dados recebidos.

### 5.2 Nao Compartilhamos Dados Com

- Redes de publicidade (Google Ads, Facebook Ads, etc.)
- Plataformas de analytics (Google Analytics, Firebase Analytics, etc.)
- Servicos de rastreamento ou remarketing
- Redes sociais
- Corretores de dados (data brokers)
- Quaisquer outros terceiros

---

## 6. Permissoes do Dispositivo

### 6.1 Permissoes Solicitadas

O BuscaCep solicita **apenas a seguinte permissao**:

| Permissao | Finalidade | Obrigatoria |
|---|---|---|
| `INTERNET` | Realizar consultas a API ViaCEP | Sim |

### 6.2 Permissoes NAO Solicitadas

O Aplicativo **NAO solicita e NAO acessa**:

- Localizacao (GPS/rede)
- Camera
- Microfone
- Contatos
- Armazenamento externo (fotos, arquivos)
- Telefone (chamadas, IMEI)
- SMS
- Calendario
- Sensores corporais
- Bluetooth

---

## 7. Seguranca dos Dados

Adotamos as seguintes medidas para proteger as informacoes transmitidas:

- **Criptografia em transito:** Todas as comunicacoes com a API ViaCEP sao realizadas via **HTTPS/TLS**, garantindo criptografia ponta-a-ponta dos dados transmitidos
- **Nenhum armazenamento persistente:** Como nao armazenamos dados, nao ha risco de vazamento de informacoes armazenadas
- **Codigo minimalista:** O app utiliza apenas as dependencias estritamente necessarias para seu funcionamento, reduzindo a superficie de ataque
- **Sem autenticacao:** Como nao ha sistema de login, nao ha credenciais que possam ser comprometidas

---

## 8. Privacidade de Criancas

O BuscaCep **NAO e direcionado a criancas menores de 13 anos** e nao coleta intencionalmente informacoes de criancas. Como o Aplicativo nao coleta dados pessoais de nenhum usuario, nao ha risco de coleta inadvertida de dados de menores.

O Aplicativo esta em conformidade com:
- **COPPA** (Children's Online Privacy Protection Act)
- **Artigo 14 da LGPD** (protecao de dados de criancas e adolescentes)

---

## 9. Seus Direitos

Mesmo que o BuscaCep nao colete dados pessoais, reconhecemos seus direitos conforme a legislacao aplicavel:

### 9.1 Sob a LGPD (Lei Geral de Protecao de Dados - Brasil)

- **Direito de confirmacao e acesso:** Voce tem o direito de confirmar que nao tratamos seus dados pessoais
- **Direito de eliminacao:** Nao ha dados a eliminar, pois nenhum dado e armazenado
- **Direito de informacao:** Esta politica detalha todas as praticas de tratamento de dados

### 9.2 Sob o GDPR (Regulamento Geral de Protecao de Dados - UE)

- **Direito de acesso:** Nenhum dado pessoal e processado
- **Direito ao esquecimento:** Nao aplicavel, pois nenhum dado e retido
- **Direito a portabilidade:** Nao aplicavel

### 9.3 Sob o CCPA (California Consumer Privacy Act - EUA)

- **Direito de saber:** Esta politica informa que nenhum dado pessoal e coletado
- **Direito de exclusao:** Nao aplicavel
- **Direito de nao venda:** Nenhum dado e vendido a terceiros

---

## 10. Retencao e Exclusao de Dados

| Aspecto | Detalhe |
|---|---|
| **Periodo de retencao** | Zero. Dados existem apenas em memoria durante o uso |
| **Exclusao automatica** | Ao fechar o app, todos os dados sao descartados |
| **Exclusao manual** | Ao limpar campos ou trocar abas, os dados sao descartados |
| **Desinstalacao** | Ao desinstalar o app, nenhum residuo de dados permanece no dispositivo |

---

## 11. Links Externos

O Aplicativo contem um link para o site do desenvolvedor ([www.leankar.dev](https://www.leankar.dev)). Ao clicar neste link, voce sera redirecionado para um site externo que possui sua propria politica de privacidade. Nao nos responsabilizamos pelas praticas de privacidade de sites externos.

---

## 12. Alteracoes nesta Politica de Privacidade

Podemos atualizar esta Politica de Privacidade periodicamente. Quando fizermos alteracoes significativas:

- A data de "Ultima atualizacao" no topo deste documento sera modificada
- As alteracoes entram em vigor imediatamente apos a publicacao
- Recomendamos que voce revise esta politica periodicamente

O uso continuado do Aplicativo apos quaisquer alteracoes constitui sua aceitacao da politica revisada.

---

## 13. Conformidade com Google Play

Esta politica foi elaborada em conformidade com as exigencias do **Google Play** para publicacao de aplicativos, incluindo:

- **Declaracao de Seguranca de Dados (Data Safety Section):** O BuscaCep declara que nao coleta nem compartilha dados de usuario
- **Politica de Dados do Usuario:** Cumprimos integralmente a politica de dados do usuario do Google Play
- **Transparencia:** Todas as praticas de tratamento de dados estao claramente descritas neste documento
- **Criptografia:** Os dados em transito sao criptografados via HTTPS

### Resumo para a secao Data Safety do Google Play

| Pergunta Google Play | Resposta |
|---|---|
| O app coleta dados do usuario? | Nao |
| O app compartilha dados com terceiros? | Nao |
| Os dados sao criptografados em transito? | Sim (HTTPS) |
| O usuario pode solicitar exclusao de dados? | Nao aplicavel (nenhum dado armazenado) |
| O app segue a Politica de Familias do Google Play? | Sim |

---

## 14. Conformidade Legal

O BuscaCep esta em conformidade com as seguintes legislacoes e regulamentacoes:

- **LGPD** - Lei Geral de Protecao de Dados (Lei n. 13.709/2018 - Brasil)
- **GDPR** - General Data Protection Regulation (Regulamento UE 2016/679)
- **CCPA** - California Consumer Privacy Act (EUA)
- **COPPA** - Children's Online Privacy Protection Act (EUA)
- **Marco Civil da Internet** (Lei n. 12.965/2014 - Brasil)
- **Politicas do Google Play** para desenvolvedores

---

## 15. Contato

Se voce tiver duvidas, preocupacoes ou solicitacoes relacionadas a esta Politica de Privacidade, entre em contato conosco:

- **Site:** [www.leankar.dev](https://www.leankar.dev)
- **Desenvolvedor:** leankar.dev

Responderemos a sua solicitacao no menor prazo possivel.

---

*Esta Politica de Privacidade se aplica exclusivamente ao aplicativo BuscaCep e nao se estende a outros aplicativos, sites ou servicos que possam ser acessados a partir deste.*

---
---

<a name="english"></a>
# English

# Privacy Policy - BuscaCep

**Last updated:** February 8, 2026

**Developer:** leankar.dev
**Contact:** [www.leankar.dev](https://www.leankar.dev)
**Application:** BuscaCep
**Package:** leankar.dev.busca_cep_app

---

## 1. Introduction

This Privacy Policy describes how the **BuscaCep** application ("we", "our", or "Application") collects, uses, stores, and protects user information ("you" or "user"). Our commitment is to transparency and the protection of your privacy.

By using BuscaCep, you agree to the practices described in this policy. If you do not agree with the terms presented here, we recommend that you do not use the Application.

---

## 2. Information We Collect

### 2.1 Personal Data

BuscaCep **does NOT collect, store, or process personal data** of any kind, including but not limited to:

- Name, email, or phone number
- Identification documents (social security number, ID, etc.)
- Location data (GPS)
- Biometric data
- Device contact information
- Photos, videos, or device files
- Unique advertising identifiers

### 2.2 Usage Data

The Application **does NOT collect usage data**, such as:

- Search history
- Application usage frequency
- Time spent on screens
- Interaction events (clicks, taps, navigation)
- Session data

### 2.3 Data Transmitted to Third Parties

During normal operation, the following data is transmitted **exclusively** to the public ViaCEP API (`https://viacep.com.br/ws`):

| Search Type | Data Transmitted | Purpose |
|---|---|---|
| Search by CEP | CEP number (8 digits) | Query the corresponding address |
| Search by Address | State (UF), city, and street | Query corresponding postal codes |

**Important:** This data (postal codes and addresses) is publicly available information and **does not constitute personal data**. Transmission is done exclusively via the **HTTPS** protocol (encrypted).

### 2.4 Automatically Collected Data

The Application **does NOT automatically collect** any type of data, including:

- IP address (not recorded by the app; may be recorded by the ViaCEP API server per their own policy)
- Device type or operating system
- Device identifiers (IMEI, Android ID, etc.)
- Cookie data or tracking technologies
- Diagnostic data or crash reports

---

## 3. How We Use Information

BuscaCep uses information entered by the user **solely** to:

- **Query addresses**: Send the postal code or address to the ViaCEP API and display the result on screen
- **Display results**: Present the address data returned by the API to the user

**We do NOT use information to:**

- Create user profiles
- Conduct targeted advertising
- Send push notifications or emails
- Analyze usage behavior
- Sell or share data with third parties
- Train artificial intelligence models

---

## 4. Data Storage

### 4.1 Local Storage

BuscaCep **does NOT store data locally** on the user's device. We do not use:

- Local databases (SQLite, Hive, Isar, etc.)
- SharedPreferences or key-value storage
- Disk cache
- Files on the device's file system

### 4.2 In-Memory Data

Search data and results are kept **exclusively in RAM** during active use of the Application. When closing the app, switching search tabs, or clearing fields, **all data is immediately and permanently discarded**.

### 4.3 Server Storage

BuscaCep **does NOT have its own servers** and **does NOT store data in the cloud**. We do not use:

- Firebase, AWS, Azure, or any cloud service
- Remote databases
- File storage services

---

## 5. Data Sharing with Third Parties

### 5.1 Third-Party Services Used

The Application uses **a single external service**:

| Service | Provider | Purpose | Shared Data |
|---|---|---|---|
| ViaCEP API | viacep.com.br | Brazilian postal code queries | Entered postal code or address |

The ViaCEP API is a **free and public** Brazilian government service for postal code queries. We recommend that users consult the ViaCEP privacy policy at [https://viacep.com.br](https://viacep.com.br) for information on how they handle received data.

### 5.2 We Do NOT Share Data With

- Advertising networks (Google Ads, Facebook Ads, etc.)
- Analytics platforms (Google Analytics, Firebase Analytics, etc.)
- Tracking or remarketing services
- Social networks
- Data brokers
- Any other third parties

---

## 6. Device Permissions

### 6.1 Requested Permissions

BuscaCep requests **only the following permission**:

| Permission | Purpose | Required |
|---|---|---|
| `INTERNET` | Make queries to the ViaCEP API | Yes |

### 6.2 Permissions NOT Requested

The Application **does NOT request and does NOT access**:

- Location (GPS/network)
- Camera
- Microphone
- Contacts
- External storage (photos, files)
- Phone (calls, IMEI)
- SMS
- Calendar
- Body sensors
- Bluetooth

---

## 7. Data Security

We adopt the following measures to protect transmitted information:

- **Encryption in transit:** All communications with the ViaCEP API are made via **HTTPS/TLS**, ensuring end-to-end encryption of transmitted data
- **No persistent storage:** Since we do not store data, there is no risk of stored information leakage
- **Minimalist code:** The app uses only the strictly necessary dependencies for its operation, reducing the attack surface
- **No authentication:** Since there is no login system, there are no credentials that can be compromised

---

## 8. Children's Privacy

BuscaCep **is NOT directed at children under 13 years of age** and does not intentionally collect information from children. Since the Application does not collect personal data from any user, there is no risk of inadvertent collection of minors' data.

The Application complies with:
- **COPPA** (Children's Online Privacy Protection Act)
- **Article 14 of the LGPD** (protection of children's and adolescents' data)

---

## 9. Your Rights

Even though BuscaCep does not collect personal data, we recognize your rights under applicable legislation:

### 9.1 Under the LGPD (General Data Protection Law - Brazil)

- **Right of confirmation and access:** You have the right to confirm that we do not process your personal data
- **Right of deletion:** There is no data to delete, as no data is stored
- **Right to information:** This policy details all data processing practices

### 9.2 Under the GDPR (General Data Protection Regulation - EU)

- **Right of access:** No personal data is processed
- **Right to be forgotten:** Not applicable, as no data is retained
- **Right to portability:** Not applicable

### 9.3 Under the CCPA (California Consumer Privacy Act - USA)

- **Right to know:** This policy informs that no personal data is collected
- **Right to deletion:** Not applicable
- **Right to opt-out of sale:** No data is sold to third parties

---

## 10. Data Retention and Deletion

| Aspect | Detail |
|---|---|
| **Retention period** | Zero. Data exists only in memory during use |
| **Automatic deletion** | When closing the app, all data is discarded |
| **Manual deletion** | When clearing fields or switching tabs, data is discarded |
| **Uninstallation** | When uninstalling the app, no data residue remains on the device |

---

## 11. External Links

The Application contains a link to the developer's website ([www.leankar.dev](https://www.leankar.dev)). By clicking this link, you will be redirected to an external website that has its own privacy policy. We are not responsible for the privacy practices of external websites.

---

## 12. Changes to This Privacy Policy

We may update this Privacy Policy periodically. When we make significant changes:

- The "Last updated" date at the top of this document will be modified
- Changes take effect immediately upon publication
- We recommend that you review this policy periodically

Continued use of the Application after any changes constitutes your acceptance of the revised policy.

---

## 13. Google Play Compliance

This policy was prepared in compliance with **Google Play** requirements for app publishing, including:

- **Data Safety Section:** BuscaCep declares that it does not collect or share user data
- **User Data Policy:** We fully comply with Google Play's user data policy
- **Transparency:** All data processing practices are clearly described in this document
- **Encryption:** Data in transit is encrypted via HTTPS

### Summary for Google Play Data Safety Section

| Google Play Question | Answer |
|---|---|
| Does the app collect user data? | No |
| Does the app share data with third parties? | No |
| Is data encrypted in transit? | Yes (HTTPS) |
| Can the user request data deletion? | Not applicable (no data stored) |
| Does the app follow Google Play's Families Policy? | Yes |

---

## 14. Legal Compliance

BuscaCep complies with the following laws and regulations:

- **LGPD** - Lei Geral de Protecao de Dados (Law No. 13,709/2018 - Brazil)
- **GDPR** - General Data Protection Regulation (EU Regulation 2016/679)
- **CCPA** - California Consumer Privacy Act (USA)
- **COPPA** - Children's Online Privacy Protection Act (USA)
- **Marco Civil da Internet** (Law No. 12,965/2014 - Brazil)
- **Google Play** Developer Policies

---

## 15. Contact

If you have questions, concerns, or requests related to this Privacy Policy, please contact us:

- **Website:** [www.leankar.dev](https://www.leankar.dev)
- **Developer:** leankar.dev

We will respond to your request as soon as possible.

---

*This Privacy Policy applies exclusively to the BuscaCep application and does not extend to other applications, websites, or services that may be accessed from it.*

---
---

<a name="espanol"></a>
# Espanol

# Politica de Privacidad - BuscaCep

**Ultima actualizacion:** 8 de febrero de 2026

**Desarrollador:** leankar.dev
**Contacto:** [www.leankar.dev](https://www.leankar.dev)
**Aplicacion:** BuscaCep
**Paquete:** leankar.dev.busca_cep_app

---

## 1. Introduccion

Esta Politica de Privacidad describe como la aplicacion **BuscaCep** ("nosotros", "nuestro" o "Aplicacion") recopila, utiliza, almacena y protege la informacion de los usuarios ("usted" o "usuario"). Nuestro compromiso es con la transparencia y la proteccion de su privacidad.

Al utilizar BuscaCep, usted acepta las practicas descritas en esta politica. Si no esta de acuerdo con los terminos aqui presentados, le recomendamos que no utilice la Aplicacion.

---

## 2. Informacion que Recopilamos

### 2.1 Datos Personales

BuscaCep **NO recopila, almacena ni procesa datos personales** de ninguna naturaleza, incluyendo, pero no limitandose a:

- Nombre, correo electronico o telefono
- Documentos de identificacion (numero de seguro social, DNI, etc.)
- Datos de ubicacion (GPS)
- Datos biometricos
- Informacion de contactos del dispositivo
- Fotos, videos o archivos del dispositivo
- Identificadores unicos de publicidad

### 2.2 Datos de Uso

La Aplicacion **NO recopila datos de uso**, tales como:

- Historial de busquedas realizadas
- Frecuencia de uso de la aplicacion
- Tiempo de permanencia en pantallas
- Eventos de interaccion (clics, toques, navegacion)
- Datos de sesion

### 2.3 Datos Transmitidos a Terceros

Durante el funcionamiento normal de la Aplicacion, los siguientes datos se transmiten **exclusivamente** a la API publica ViaCEP (`https://viacep.com.br/ws`):

| Tipo de Busqueda | Datos Transmitidos | Finalidad |
|---|---|---|
| Busqueda por CEP | Numero del CEP (8 digitos) | Consultar la direccion correspondiente |
| Busqueda por Direccion | Estado (UF), ciudad y calle | Consultar codigos postales correspondientes |

**Importante:** Estos datos (codigos postales y direcciones) son informacion de naturaleza publica y **no constituyen datos personales**. La transmision se realiza exclusivamente via protocolo **HTTPS** (encriptado).

### 2.4 Datos Recopilados Automaticamente

La Aplicacion **NO recopila automaticamente** ningun tipo de dato, incluyendo:

- Direccion IP (no registrada por la app; puede ser registrada por el servidor de la API ViaCEP segun su propia politica)
- Tipo de dispositivo o sistema operativo
- Identificadores de dispositivo (IMEI, Android ID, etc.)
- Datos de cookies o tecnologias de rastreo
- Datos de diagnostico o reportes de errores

---

## 3. Como Utilizamos la Informacion

BuscaCep utiliza la informacion ingresada por el usuario **unicamente** para:

- **Consultar direcciones**: Enviar el codigo postal o direccion a la API ViaCEP y mostrar el resultado en pantalla
- **Mostrar resultados**: Presentar los datos de direccion devueltos por la API al usuario

**NO utilizamos la informacion para:**

- Crear perfiles de usuario
- Realizar publicidad dirigida
- Enviar notificaciones push o correos electronicos
- Analizar comportamiento de uso
- Comercializar o compartir datos con terceros
- Entrenar modelos de inteligencia artificial

---

## 4. Almacenamiento de Datos

### 4.1 Almacenamiento Local

BuscaCep **NO almacena datos localmente** en el dispositivo del usuario. No utilizamos:

- Bases de datos locales (SQLite, Hive, Isar, etc.)
- SharedPreferences o almacenamiento clave-valor
- Cache en disco
- Archivos en el sistema de archivos del dispositivo

### 4.2 Datos en Memoria

Los datos de busqueda y resultados se mantienen **exclusivamente en la memoria RAM** durante el uso activo de la Aplicacion. Al cerrar la app, cambiar de pestaña de busqueda o limpiar los campos, **todos los datos se descartan inmediata y permanentemente**.

### 4.3 Almacenamiento en Servidores

BuscaCep **NO posee servidores propios** y **NO almacena datos en la nube**. No utilizamos:

- Firebase, AWS, Azure o cualquier servicio en la nube
- Bases de datos remotas
- Servicios de almacenamiento de archivos

---

## 5. Compartir Datos con Terceros

### 5.1 Servicios de Terceros Utilizados

La Aplicacion utiliza **un unico servicio externo**:

| Servicio | Proveedor | Finalidad | Datos Compartidos |
|---|---|---|---|
| API ViaCEP | viacep.com.br | Consulta de codigos postales brasileños | Codigo postal o direccion ingresada |

La API ViaCEP es un servicio **publico y gratuito** del gobierno brasileño para consulta de codigos postales. Recomendamos que el usuario consulte la politica de privacidad de ViaCEP en [https://viacep.com.br](https://viacep.com.br) para informacion sobre como manejan los datos recibidos.

### 5.2 NO Compartimos Datos Con

- Redes de publicidad (Google Ads, Facebook Ads, etc.)
- Plataformas de analytics (Google Analytics, Firebase Analytics, etc.)
- Servicios de rastreo o remarketing
- Redes sociales
- Corredores de datos (data brokers)
- Cualquier otro tercero

---

## 6. Permisos del Dispositivo

### 6.1 Permisos Solicitados

BuscaCep solicita **unicamente el siguiente permiso**:

| Permiso | Finalidad | Obligatorio |
|---|---|---|
| `INTERNET` | Realizar consultas a la API ViaCEP | Si |

### 6.2 Permisos NO Solicitados

La Aplicacion **NO solicita y NO accede a**:

- Ubicacion (GPS/red)
- Camara
- Microfono
- Contactos
- Almacenamiento externo (fotos, archivos)
- Telefono (llamadas, IMEI)
- SMS
- Calendario
- Sensores corporales
- Bluetooth

---

## 7. Seguridad de los Datos

Adoptamos las siguientes medidas para proteger la informacion transmitida:

- **Encriptacion en transito:** Todas las comunicaciones con la API ViaCEP se realizan via **HTTPS/TLS**, garantizando encriptacion de extremo a extremo de los datos transmitidos
- **Sin almacenamiento persistente:** Como no almacenamos datos, no hay riesgo de filtracion de informacion almacenada
- **Codigo minimalista:** La app utiliza solo las dependencias estrictamente necesarias para su funcionamiento, reduciendo la superficie de ataque
- **Sin autenticacion:** Como no hay sistema de inicio de sesion, no hay credenciales que puedan ser comprometidas

---

## 8. Privacidad de los Niños

BuscaCep **NO esta dirigido a niños menores de 13 años** y no recopila intencionalmente informacion de niños. Como la Aplicacion no recopila datos personales de ningun usuario, no hay riesgo de recopilacion inadvertida de datos de menores.

La Aplicacion cumple con:
- **COPPA** (Children's Online Privacy Protection Act)
- **Articulo 14 de la LGPD** (proteccion de datos de niños y adolescentes)

---

## 9. Sus Derechos

Aunque BuscaCep no recopila datos personales, reconocemos sus derechos conforme a la legislacion aplicable:

### 9.1 Bajo la LGPD (Ley General de Proteccion de Datos - Brasil)

- **Derecho de confirmacion y acceso:** Usted tiene derecho a confirmar que no procesamos sus datos personales
- **Derecho de eliminacion:** No hay datos que eliminar, ya que ningun dato se almacena
- **Derecho a la informacion:** Esta politica detalla todas las practicas de tratamiento de datos

### 9.2 Bajo el GDPR (Reglamento General de Proteccion de Datos - UE)

- **Derecho de acceso:** Ningun dato personal es procesado
- **Derecho al olvido:** No aplicable, ya que ningun dato es retenido
- **Derecho a la portabilidad:** No aplicable

### 9.3 Bajo la CCPA (California Consumer Privacy Act - EE.UU.)

- **Derecho a saber:** Esta politica informa que ningun dato personal es recopilado
- **Derecho de eliminacion:** No aplicable
- **Derecho a la no venta:** Ningun dato se vende a terceros

---

## 10. Retencion y Eliminacion de Datos

| Aspecto | Detalle |
|---|---|
| **Periodo de retencion** | Cero. Los datos existen solo en memoria durante el uso |
| **Eliminacion automatica** | Al cerrar la app, todos los datos se descartan |
| **Eliminacion manual** | Al limpiar campos o cambiar pestañas, los datos se descartan |
| **Desinstalacion** | Al desinstalar la app, ningun residuo de datos permanece en el dispositivo |

---

## 11. Enlaces Externos

La Aplicacion contiene un enlace al sitio web del desarrollador ([www.leankar.dev](https://www.leankar.dev)). Al hacer clic en este enlace, sera redirigido a un sitio web externo que tiene su propia politica de privacidad. No nos responsabilizamos por las practicas de privacidad de sitios web externos.

---

## 12. Cambios en esta Politica de Privacidad

Podemos actualizar esta Politica de Privacidad periodicamente. Cuando realicemos cambios significativos:

- La fecha de "Ultima actualizacion" en la parte superior de este documento sera modificada
- Los cambios entran en vigor inmediatamente despues de la publicacion
- Recomendamos que revise esta politica periodicamente

El uso continuado de la Aplicacion despues de cualquier cambio constituye su aceptacion de la politica revisada.

---

## 13. Cumplimiento con Google Play

Esta politica fue elaborada en cumplimiento con los requisitos de **Google Play** para la publicacion de aplicaciones, incluyendo:

- **Seccion de Seguridad de Datos (Data Safety Section):** BuscaCep declara que no recopila ni comparte datos de usuario
- **Politica de Datos del Usuario:** Cumplimos integramente con la politica de datos del usuario de Google Play
- **Transparencia:** Todas las practicas de tratamiento de datos estan claramente descritas en este documento
- **Encriptacion:** Los datos en transito estan encriptados via HTTPS

### Resumen para la seccion Data Safety de Google Play

| Pregunta Google Play | Respuesta |
|---|---|
| ¿La app recopila datos del usuario? | No |
| ¿La app comparte datos con terceros? | No |
| ¿Los datos estan encriptados en transito? | Si (HTTPS) |
| ¿El usuario puede solicitar eliminacion de datos? | No aplicable (ningun dato almacenado) |
| ¿La app sigue la Politica de Familias de Google Play? | Si |

---

## 14. Cumplimiento Legal

BuscaCep cumple con las siguientes leyes y regulaciones:

- **LGPD** - Lei Geral de Protecao de Dados (Ley No. 13.709/2018 - Brasil)
- **GDPR** - General Data Protection Regulation (Reglamento UE 2016/679)
- **CCPA** - California Consumer Privacy Act (EE.UU.)
- **COPPA** - Children's Online Privacy Protection Act (EE.UU.)
- **Marco Civil da Internet** (Ley No. 12.965/2014 - Brasil)
- **Politicas de Google Play** para desarrolladores

---

## 15. Contacto

Si tiene preguntas, inquietudes o solicitudes relacionadas con esta Politica de Privacidad, contactenos:

- **Sitio web:** [www.leankar.dev](https://www.leankar.dev)
- **Desarrollador:** leankar.dev

Responderemos a su solicitud en el menor plazo posible.

---

*Esta Politica de Privacidad se aplica exclusivamente a la aplicacion BuscaCep y no se extiende a otras aplicaciones, sitios web o servicios que puedan ser accedidos desde ella.*
