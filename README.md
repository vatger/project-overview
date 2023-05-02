# Projects Overview (TBD!)

Clicking on the project name will guide you to the repository of the project.

### VATGER Projects

tbd.

### ATD Projects

| Projects              | Status    | Person responsible  | required Skills |
|-----------------------|-----------|---------------------|-----------------|
| ScenarioFileGenerator | see below | Leon K. / Julian S. | see below       |
| EndorsementChecker    | see below | Leon K.             | see below       |

### NAV Projects

| Projects         | Status | Person responsible | required Skills |
|------------------|--------|--------------------|-----------------|
| [vACDM][vacdm]   | OB     | Moritz F., Phil H. | see below       |
| [vSID][vsid]     | CD     | Phil H.            | see below       |
| [vTFDPS][vtfdps] | CD     | Leon K.            | see below       |
| LoA Finder       | -      | Paul à B.          | C++             |

| Projects     | Status   | Person responsible  | required Skills   |
|--------------|----------|---------------------|-------------------|
| Tourensystem | PL | Julian S., Fionn S. | Typescript, React |


### Status codes:
```
OB - Open Beta
CD - Concept Development
PL - Planning
```

## Description of Projects

#### ATD Projects

<details>
    <summary>ScenarioFileGenerator</summary>
    Multiple people have developed different programs or script that make the creation of scenario files for Euroscope Simulator Session much easier and more automated.
    The projects are written in C#, PHP, JS & HTML or Python.
    The goal is to a create a) project which combines all of these projects and their individual benefits and b) create a project which is centrally accessible to all.
    Current versions of the projects can already be configured for individual airports.
    If interested feel free to contact Leon K.
</details>
<br>
<details>
    <summary>EndorsementChecker</summary>
    A program (currently) built using C# and WPF to check hours spent on Vatsim positions and based on this data determine if a person adhers to a given endorsement policy.
    Outputs this data as list in excel and in HTML code to allow editing and displaying of current endorsements.
</details>

#### NAV Projects

<details>
  <summary>vSID</summary>

Euroscope Plugin for:
Automatic assignment of SIDs based on given parameters, such as preferential runway, wake turbulence category [...].
Automatic entry of initial climb and indication of climb via phraseology based on chosen SID.

</details>
<br>
<details>
  <summary>vTFDPS</summary>

The aim of this project is to replicate a real Tower Flight Data Processing System and bring electronic flight strips to Vatsim.

This project currently contains three components.
The main application is built using Flutter.
A backend server used to exchange data, which is not available in Euroscope and thereby can not be transferred via Euroscope.
A Euroscope Plugin allows the data exchange between Euroscope and Flutter application or backend server.

</details>
<br>
<details>
  <summary>LoA Finder</summary>

A Euroscope plugin which aims to provide better information about agreements. It is supposed to determine agreements based on live traffic and stations online, while also displaying the releases agreed between both sectors.

</details>

#### Event Projects

[vsid]: https://git.vatsim-germany.org/vatger-projects/vsid
[vacdm]: https://github.com/vACDM
[vtfdps]: https://github.com/orgs/vtfdps/
