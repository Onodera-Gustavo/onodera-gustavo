<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,55:161B22,100:3FB950&height=170&section=header&text=Gustavo%20Sousa%20Gomes&fontSize=46&fontColor=3FB950&animation=fadeIn&fontAlignY=36&desc=Estagi%C3%A1rio%20de%20Engenharia%20de%20Dados%20%7C%20C%23%2F.NET%2C%20SQL%20e%20Azure&descAlignY=58&descSize=17&descColor=E3B341"/>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=21&pause=1200&color=3FB950&background=0D111700&center=true&vCenter=true&width=760&lines=%24+monitorar+banco%2C+medir+qualidade%2C+validar+por+replay;%24+C%23%2F.NET+8+%2B+SQL+%2B+Azure+em+produ%C3%A7%C3%A3o;%24+Ci%C3%AAncia+da+Computa%C3%A7%C3%A3o%2C+FAM%2C+previs%C3%A3o+2028)](https://git.io/typing-svg)

<img src="https://img.shields.io/badge/S%C3%A3o%20Paulo-SP-3FB950?style=flat-square&labelColor=161B22&logo=googlemaps&logoColor=3FB950"/>
<img src="https://img.shields.io/badge/M3BS%20Advogados-desde%20mar%2F2026-E3B341?style=flat-square&labelColor=161B22"/>
<img src="https://img.shields.io/badge/PT-nativo-C9D1D9?style=flat-square&labelColor=161B22"/>
<img src="https://img.shields.io/badge/EN-fluente-C9D1D9?style=flat-square&labelColor=161B22"/>
<img src="https://img.shields.io/badge/ES-b%C3%A1sico-C9D1D9?style=flat-square&labelColor=161B22"/>

</div>

<br/>

## `> whoami`

```console
gustavo@dev:~$ whoami
Estagiário de Engenharia de Dados na M3BS Advogados (São Paulo, SP).
Escrevo C#/.NET 8 e SQL que rodam no Azure, em produção.
Monitor de banco, métrica de qualidade de dados, deduplicação e reconciliação validadas por replay.
```

> Código de trabalho fica nos repositórios privados do empregador. O que aparece aqui é o lado pessoal do terminal.

<br/>

## `> cat sobre.md`

Estudante de Ciência da Computação no Centro Universitário FAM, com conclusão prevista para dez/2028. Técnico em Análise e Desenvolvimento de Sistemas pelo SENAI, concluído em dez/2025.

Gosto de sistemas que se explicam sozinhos: monitoramento, alertas, testes e números que provam o que o código faz. Prefiro provar com replay e auditoria a confiar no "parece certo".

Antes do estágio atual, fui aprendiz de desenvolvimento de sistemas em indústria de plásticos (fev/2024 a dez/2025) e migrei cerca de 500 fichas em papel do setor de saúde para um banco SQL, com Python.

<br/>

## `> ls ~/trabalho --details`

O que faço hoje na M3BS Advogados, estágio em Engenharia de Dados desde mar/2026.

- **`[monitor]`** Monitor somente leitura de Azure SQL (DMVs, Query Store) e das cargas de ingestão, em C#/.NET 8. Roda em Azure Automation com coleta leve e alertas a cada 15 minutos.
- **`[qualidade]`** Mostrei que cerca de 95% das tarefas contadas como atrasadas eram falsos positivos. Criei uma métrica semanal de qualidade, em produção, com modo de verificação por recontagem SQL e amostragem via API.
- **`[replay]`** Reproduzi em C#, em modo sombra, o roteamento e a deduplicação de publicações judiciais. 100% de concordância de área no replay de mais de 3 mil publicações reais, com mais de 100 testes xUnit.
- **`[reconciliação]`** Reconciliador somente leitura entre portal de cliente, planilha e Legal One, com chave composta e 51 testes xUnit. Na auditoria manual, dispensou 15 dos 19 alertas da comparação por processo.
- **`[operação]`** Operei por delegação a esteira de publicações (Power Automate, Azure Functions, robôs Python). Com falha rápida no retry de uma etapa acessória, a execução seguinte levou 8 minutos, contra 3 a 4 horas.
- **`[ingestão]`** Contribuí com o framework de ingestão da equipe (API OData do Legal One para Azure SQL): converti sub-recursos de 5 entidades em colunas e validei as cargas em banco de teste clonado.

<br/>

## `> tech --stack`

<table align="center">
  <tr>
    <td align="center" width="180"><b>Linguagens</b></td>
    <td align="center"><img src="https://skillicons.dev/icons?i=cs,python,powershell&theme=dark"/></td>
    <td>C# (.NET 8), SQL (T-SQL), PowerShell, Python (pipeline pessoal e scripts)</td>
  </tr>
  <tr>
    <td align="center"><b>Dados</b></td>
    <td align="center"><img src="https://skillicons.dev/icons?i=azure&theme=dark"/> <img height="48" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/microsoftsqlserver/microsoftsqlserver-original.svg"/></td>
    <td>Azure SQL Database e SQL Server (DMVs, Query Store), DuckDB e Parquet, ingestão incremental, ETL, qualidade e reconciliação de dados, validação por replay, Excel (OpenXML), Power BI (leitura de DAX e Power Query M)</td>
  </tr>
  <tr>
    <td align="center"><b>Cloud e integração</b></td>
    <td align="center"><img src="https://skillicons.dev/icons?i=azure&theme=dark"/></td>
    <td>Azure Automation (runbooks), identidade gerenciada (Entra ID), Azure Blob Storage, APIs REST (OData), Microsoft Graph e SharePoint, Power Automate e Azure Functions (operação)</td>
  </tr>
  <tr>
    <td align="center"><b>Engenharia</b></td>
    <td align="center"><img src="https://skillicons.dev/icons?i=git,github,githubactions&theme=dark"/></td>
    <td>Testes automatizados (xUnit, pytest), pull requests com revisão de código, CI no GitHub Actions, monitoramento, observabilidade e alertas, desenvolvimento assistido por IA (Claude Code)</td>
  </tr>
  <tr>
    <td align="center"><b>Web (projetos pessoais)</b></td>
    <td align="center"><img src="https://skillicons.dev/icons?i=django&theme=dark"/></td>
    <td>Django, com testes automatizados e CI</td>
  </tr>
</table>

<br/>

## `> ls ~/projetos --featured`

<table align="center">
  <tr>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/Onodera-Gustavo/W-H-Y">W-H-Y</a></h3>
      <p align="center">
        <img src="https://img.shields.io/badge/Python-3FB950?style=flat-square&labelColor=161B22&logo=python&logoColor=3FB950"/>
        <img src="https://img.shields.io/badge/DuckDB-E3B341?style=flat-square&labelColor=161B22"/>
        <img src="https://img.shields.io/badge/GitHub%20Actions-C9D1D9?style=flat-square&labelColor=161B22&logo=githubactions&logoColor=C9D1D9"/>
      </p>
      <p>Pipeline diário de manchetes com análise de sentimento. Coleta RSS agendada no GitHub Actions, histórico deduplicado em DuckDB e Parquet, sentimento com VADER e FinBERT e medição de concordância entre os dois (kappa de Cohen). 45 testes pytest.</p>
      <p align="center">
        <a href="https://onodera-gustavo.github.io/W-H-Y"><img src="https://img.shields.io/badge/demo%20ao%20vivo-3FB950?style=for-the-badge&labelColor=161B22&logo=githubpages&logoColor=3FB950"/></a>
        <a href="https://github.com/Onodera-Gustavo/W-H-Y"><img src="https://img.shields.io/badge/c%C3%B3digo-E3B341?style=for-the-badge&labelColor=161B22&logo=github&logoColor=E3B341"/></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/Onodera-Gustavo/Superbook-Project">Superbook</a></h3>
      <p align="center">
        <img src="https://img.shields.io/badge/Python-3FB950?style=flat-square&labelColor=161B22&logo=python&logoColor=3FB950"/>
        <img src="https://img.shields.io/badge/Django-E3B341?style=flat-square&labelColor=161B22&logo=django&logoColor=E3B341"/>
        <img src="https://img.shields.io/badge/CI-C9D1D9?style=flat-square&labelColor=161B22&logo=githubactions&logoColor=C9D1D9"/>
      </p>
      <p>Rede social de heróis em Django, com testes automatizados e CI.</p>
      <p align="center">
        <a href="https://github.com/Onodera-Gustavo/Superbook-Project"><img src="https://img.shields.io/badge/c%C3%B3digo-E3B341?style=for-the-badge&labelColor=161B22&logo=github&logoColor=E3B341"/></a>
      </p>
    </td>
  </tr>
</table>

<details>
<summary><code>ls ~/projetos --all</code></summary>
<br/>

- [Legacy-senai](https://github.com/Onodera-Gustavo/Legacy-senai): repositório da época do curso técnico no SENAI.

</details>

<br/>

## `> cat formacao.md`

| Curso | Instituição | Status |
|---|---|---|
| Bacharelado em Ciência da Computação | Centro Universitário FAM | previsão de conclusão: dez/2028 |
| Técnico em Análise e Desenvolvimento de Sistemas | SENAI Morvan Figueiredo | concluído em dez/2025 |

Scrum Master em projeto de equipe de 7 pessoas durante a formação técnica.

<br/>

## `> certs --verify`

| Certificado | Emissor | Data |
|---|---|---|
| Google Cloud Engineering Certificate (Google Cloud Career Launchpad) | Google Cloud | jul/2026 |
| Skill badge: Derive Insights from BigQuery Data | Google Cloud | nov/2025 |
| Python Essentials 1 e 2 | Cisco Networking Academy e OpenEDG Python Institute | fev/2025 e mai/2025 |
| Skill badge: Build Infrastructure with Terraform on Google Cloud | Google Cloud | nov/2024 |
| AWS Academy Graduate, Cloud Foundations (curso) | AWS Academy | mar/2024 |

<div align="center">

[![Credly](https://img.shields.io/badge/verificar%20no%20Credly-3FB950?style=for-the-badge&labelColor=161B22&logo=credly&logoColor=3FB950)](https://www.credly.com/users/gustavo-sousa.f7e01f24)

</div>

<br/>

## `> git log --stat`

<div align="center">

<img height="165" src="https://github-readme-streak-stats.herokuapp.com?user=Onodera-Gustavo&hide_border=true&background=0D1117&stroke=30363D&ring=3FB950&fire=E3B341&currStreakNum=C9D1D9&sideNums=C9D1D9&currStreakLabel=3FB950&sideLabels=3FB950&dates=8B949E&locale=pt_BR"/>

</div>

<br/>

## `> snake --contributions`

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/onodera-gustavo/onodera-gustavo/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/onodera-gustavo/onodera-gustavo/output/github-contribution-grid-snake.svg">
    <img alt="Snake contribution grid" src="https://raw.githubusercontent.com/onodera-gustavo/onodera-gustavo/output/github-contribution-grid-snake.svg">
  </picture>
</div>

<br/>

## `> contact --me`

<div align="center">

[![Gmail](https://img.shields.io/badge/gustavoisinreality%40gmail.com-3FB950?style=for-the-badge&labelColor=161B22&logo=gmail&logoColor=3FB950)](mailto:gustavoisinreality@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-E3B341?style=for-the-badge&labelColor=161B22&logo=linkedin&logoColor=E3B341)](https://www.linkedin.com/in/gustavosousareal/)
[![Credly](https://img.shields.io/badge/Credly-C9D1D9?style=for-the-badge&labelColor=161B22&logo=credly&logoColor=C9D1D9)](https://www.credly.com/users/gustavo-sousa.f7e01f24)

```console
gustavo@dev:~$ exit
Obrigado pela visita. Sessão encerrada.
```

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:3FB950,45:161B22,100:0D1117&height=120&section=footer"/>
