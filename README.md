<!-- BACK TO TOP ANCHOR -->
<a id="readme-top"></a>

<!-- LOGO -->
<div align="center">
  <a href="https://leonardo-vasconcellos.vercel.app/portfolio/sbes">
    <img src="rip/imagens/cabecalho.jpg" alt="Logo" height="80" />
  </a>

  <h1 align="center">Projeto Social Futura</h1>

  <p align="center">A PHP/MySQL records and case-management system built for Joinville City Hall's Department of Social Welfare, replacing paper family registries with searchable digital households, benefit tracking, and audit-ready printed reports.</p>

  <p align="center">// government records · Secretaria do Bem Estar Social</p>

  <br />

  <a href="https://leonardo-vasconcellos.vercel.app/portfolio/sbes"
    ><strong>View it live »</strong></a>
</div>

<br />

<!-- SHIELDS -->
<div align="center">

[![Creator Website][website-shield]][website-url]
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
[![Released][year-shield]][year-url]

</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#screenshots">Screenshots</a></li>
    <li><a href="#built-with">Built With</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributors">Contributors</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Screenshot][product-screenshot]](https://leonardo-vasconcellos.vercel.app/portfolio/sbes)

<!-- PROJECT INTRO: 260 chars max -->

A PHP/MySQL records system built for Joinville City Hall's Department of Social Welfare, replacing paper family registries with searchable households, benefit tracking, and audit-ready printed reports.

<!-- END INTRO -->

SBES (Secretaria do Bem Estar Social) is a records and case-management system built for the city of Joinville's Department of Social Welfare. Internally branded "Projeto Social Futura — Gestão Social," it replaced a paper-based filing process for tracking families enrolled in municipal social assistance programs.

The system centers on two core records: the Domicílio (household) and the Pessoa (person), each tied to a physical address and socioeconomic profile. From there, caseworkers enroll a household in one or more Programas Sociais (social programs — food assistance, gas vouchers, etc.), log Benefícios (benefit disbursements) against that enrollment, and keep a running Histórico (case history) for each family.

Access is split across four roles — Operador, Assistente Social, Secretário, and Administrador — each surfaced as its own tab on the home dashboard, so a front-line caseworker and the department secretary see only the actions relevant to their job. Two printable reports close the loop with the city's audit requirements: a Ficha de Usuário (per-family case file) and a Recebimento de Benefício (proof-of-benefit receipt), both rendered as print-ready HTML directly from the database.

Key features built for this project:

- Replaced paper-based family registries (household + person records) with a searchable digital database, cutting the time caseworkers spent locating a family's history from manual filing to a single search.
- Built a role-based workflow (Operador, Assistente Social, Secretário, Administrador) so each tier of City Hall staff saw only the actions relevant to their job, reducing training overhead and data-entry errors.
- Implemented print-ready HTML reports (per-family case file, proof-of-benefit-received receipt) generated straight from the database, giving the department auditable records without manual transcription.

Built in PHP 4 against a MySQL backend, the system was developed and deployed for Joinville's City Hall in 2005. This repository preserves a wget-crawled archive of the live application (`rip/`) alongside the original PHP source (`www/`) and database schema (`db/sbes.sql`).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SCREENSHOTS -->
## Screenshots

<div align="center" style="display:flex;flex-wrap:wrap;gap:8px;justify-content:center;">
  <a href="screenshoots/01%20-%20Login.jpg"><img src="screenshoots/01%20-%20Login.jpg" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshoots/03%20-%20Ficha%20do%20Domic%C3%ADlio.jpg"><img src="screenshoots/03%20-%20Ficha%20do%20Domic%C3%ADlio.jpg" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshoots/04%20-%20Relatorio%20Beneficios.jpg"><img src="screenshoots/04%20-%20Relatorio%20Beneficios.jpg" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshoots/05%20-%20Busca%20Relatorio.jpg"><img src="screenshoots/05%20-%20Busca%20Relatorio.jpg" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshoots/06%20-%20Socio%20Economico.jpg"><img src="screenshoots/06%20-%20Socio%20Economico.jpg" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshoots/07%20-%20Programa%20Social.jpg"><img src="screenshoots/07%20-%20Programa%20Social.jpg" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshoots/08%20-%20Usuario.jpg"><img src="screenshoots/08%20-%20Usuario.jpg" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshoots/02%20-%20Home.jpg"><img src="screenshoots/02%20-%20Home.jpg" height="220" style="object-fit:cover;border-radius:6px;" /></a>
</div>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- BUILT WITH -->
## Built With

<!-- LANGUAGES -->

**Languages**

|                                                                                                                | Language | Version |
| -------------------------------------------------------------------------------------------------------------- | -------- | ------- |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="20" />           | HTML     | 5       |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="20" />             | CSS      | 3       |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" width="20" />               | PHP      | 4.3.4   |

<!-- FRAMEWORKS & LIBRARIES -->

**Frameworks & Libraries**

|                                                                                                                  | Framework | Version |
| ---------------------------------------------------------------------------------------------------------------- | --------- | ------- |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" width="20" />             | MySQL     | 4.1.0   |

<!-- GETTING STARTED -->
## Getting Started

1. Criar Banco de dados "sbes"
2. Executar script sbes.sql no banco para criar as tabelas
3. editar o arquivo includes/conectar_mysql.php e informar host, login e senha para o banco.
4. abrir no navegador "http://host/sbes/index.php
5. Login: super / Senha: super

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

This project repository is for archive purposes only. No new features or issues are being tracked.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTORS -->
## Contributors

<a href="https://github.com/llvasconcellos2/sbes/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=llvasconcellos2/sbes" alt="Contributors" />
</a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

[Leonardo Vasconcellos - Website](https://leonardo-vasconcellos.vercel.app/) — [LinkedIn](https://www.linkedin.com/in/llvasconcellos)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->

[website-shield]: https://img.shields.io/badge/Creator_Website-%E2%86%97-2eba7a?style=for-the-badge
[website-url]: https://leonardo-vasconcellos.vercel.app/
[contributors-shield]: https://img.shields.io/github/contributors/llvasconcellos2/sbes.svg?style=for-the-badge
[contributors-url]: https://github.com/llvasconcellos2/sbes/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/llvasconcellos2/sbes.svg?style=for-the-badge
[forks-url]: https://github.com/llvasconcellos2/sbes/network/members
[issues-shield]: https://img.shields.io/github/issues/llvasconcellos2/sbes.svg?style=for-the-badge
[issues-url]: https://github.com/llvasconcellos2/sbes/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white
[linkedin-url]: https://www.linkedin.com/in/llvasconcellos
[year-shield]: https://img.shields.io/badge/Released-2005-gray?style=for-the-badge
[year-url]: #
[product-screenshot]: screenshoots/02%20-%20Home.jpg
