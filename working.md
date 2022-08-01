---
layout: page
title: "Working for TurtleSec"
description: Benefits and Policies for TurtleSec Employees
sitemap:
priority: 0.7
lastmod: 2022-08-01
changefreq: weekly
---

# Working for TurtleSec

## Table of Contents

* [About TurtleSec](#turtlesec)
* [Learning](#learning)
* [Work](#work)

<!--- TODO
* [Norway](#norway)
--->

## TurtleSec

TurtleSec is a small firm that provides contracting, consulting and training services in the area of programming and security.

### Culture

We want our company to be a good place to work and provide the foundation, safety and stability for a good life for all our employees. We are professionals who like to learn and do quality work. But life is more than work, and our primary duty is to our employees and their families.

Over the next few years we want to continue to build a team that reflects the society we are in, with a broad skill-set in the area of programming and security. We believe psychological safety and a diverse team is foundational for bringing out the best in us all.

### What do we do?

Most of our income comes from contracting work (often called consulting in Norway) for clients. The contracts are often regular software development contracts, but we also bring with us our secondary skill-set in security and try to use that to improve our clients security posture. We are focused on programming in a DevOps oriented organization. Each contract is generally around 6-12 months and are often extended. As a TurtleSec employee you will have a lot of influence on which type of contracting work you would like to do, for which client and the duration you want to stay there.

We also do trainings and workshops primarily in the area of secure programming and culture.

### Who works here?

Today we are five employees, all programmers, two with a strong Java focus, one with a strong Python focus and two with a strong C++ focus. We are all senior programmers with between 5 and 15 years of experience.

### How do we influence what we do?

We know that developing and maintaining a skill-set is crucial for having a career in tech. We will support you in your development in the direction you'd like to move career-wise. We can do this through training, and also through carefully selecting clients that will move you in the direction you would like to go. That includes what kind of technology you work with and what kind of role you take in the client organization. It might also mean giving you training and/or certifying you in technologies that will make that move easier.

### Office

Our office is in an old building from 1880 close to St. Olavs plass in downtown Oslo, Norway. Buses, trams, subways and trains are within walking distance. The office has two roomy team offices with high ceilings, original hardwood floors and crown molding. It also has a meeting room, a kitchen area and a unisex toilet. A shower is in the basement, but this is shared with other tenants. Bicycle parking is in the courtyard which also has a garden. The building and its neighbor have a lot of artists as tenants, so it is normal to see art lying around.

### Charity

1% of everything we earn is donated to charities in December each year. This has been our policy since the beginning. Which charities we donate to will be decided together with our employees each year.

### Ownership

The company is privately owned by Patricia Aas and Dag Fridtun and has no investors. It has been profitable from the start in 2018.

### Company structure

The CEO of TurtleSec is Dag Fridtun and the Chair of the board is Patricia Aas, they are both also employees and work for clients as all other employees.

## Learning

In a field which requires us to be up to date on technologies that are constantly evolving, it is important to invest in our employees' development.

### Conferences

At least one conference a year as an attendee. As a speaker, more will of course be allowed. Tickets, travel, accomodation and meals that are not covered by the conference will be covered by TurtleSec.

### Training

At least one training a year, more if needed. Expenses for trainings are of course covered by TurtleSec.

### Books or other learning tools

All books or online resources will be covered by TurtleSec.

### Equipment

Company laptop, noise cancelling headphones, mobile phone and subscription are all provided by TurtleSec. Other equipment needed will also be provided, also for the home office, examples include external screens, adaptors, camera, microphone etc.

### Open Source

Employees are encouraged to contribute to OSS and Open Source should be the default for anything we develop outside of client owned software.

### Between clients

A TurtleSec employee that is between clients will receive their regular salary and benefits just like everyone else. They can spend the time improving their competence either through training, certifications and/or work on internal Open Source projects.

In this period TurtleSec will work with sourcing possible clients, crafting CVs, making offers on contracts and other needed tasks to get an appropriate new contract. Some interviewing internally for CVs and offer letters will require the assistance of the employee, and as the process moves along there will be interviews by clients.

## Work

A lot of what we describe in this section is just Norwegian law, however, many people are not aware of their workers rights, so we feel it is important to be explicit. Norwegian law takes precedence over the below, though we in some areas allow more than the law requires.

### Hours

TurtleSec employees have a flexible 37.5 hour work week, Monday to Friday. Since the hours are flexible, employees can choose to work more some days to work less others. These "plus hours" (“plusstimer”) can be collected and taken in days off as well. If one has "minus hours" one can work them in or chose to take them off as unpaid leave. TurtleSec does not have any fixed "core hours" where one has to be working, but a client might and in that case the client's "core hours" will as a rule be followed. "Core hours" in Norway are often from 9/10 am to 14/15 pm.

### Pay and the pay adjustment process

The salaries at TurtleSec are based on the pay statistics from the STEM union [Tekna][1] from the previous year, the difference between the Masters and the Bachelors salary is based on the average difference from the union [NITO][5]. The numbers are a manually smoothed average between the upper quartile and the 90th percentile adjusted for the projected pay raise for the current year.

Those numbers are presented here in these tables, one for a Bachelors degree and one for a Masters degree, where the x axis is years of experience, and the salaries are in 1000 NOK. Years of experience is used in place of graduation year to accommodate folks that worked professionally before getting their degree.

<canvas id="bar-chart-bachelor" width="800" height="450" style="margin-bottom:50px"></canvas>
<canvas id="bar-chart-master" width="800" height="450" style="margin-bottom:50px"></canvas>
<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<script>
// Bachelor
new Chart(document.getElementById("bar-chart-bachelor"), {
    type: 'bar',
    data: {
      labels: ['2','3','4','5','6','7','8','9','10','11','12','13','14','15','16','17','18','19','20','21','22'],
      datasets: [
       {
            barPercentage: 1.0,
            order: 1,
            label: 'Bachelor Salary',
            data: [566,617,669,712,754,795,837,876,915,953,988,1019,1050,1076,1102,1123,1143,1165,1185,1206,1218],
            backgroundColor: [
                'rgba(255, 99, 132, 0.5)',
                'rgba(255, 159, 64, 0.5)',
                'rgba(255, 205, 86, 0.5)',
                'rgba(75, 192, 192, 0.5)',
                'rgba(54, 162, 235, 0.5)',
                'rgba(153, 102, 255, 0.5)',
                'rgba(201, 203, 207, 0.5)',
                'rgba(255, 99, 132, 0.5)',
                'rgba(255, 159, 64, 0.5)',
                'rgba(255, 205, 86, 0.5)',
                'rgba(75, 192, 192, 0.5)',
                'rgba(54, 162, 235, 0.5)',
                'rgba(153, 102, 255, 0.5)',
                'rgba(201, 203, 207, 0.5)',
                'rgba(255, 99, 132, 0.5)',
                'rgba(255, 159, 64, 0.5)',
                'rgba(255, 205, 86, 0.5)',
                'rgba(75, 192, 192, 0.5)',
                'rgba(54, 162, 235, 0.5)',
                'rgba(153, 102, 255, 0.5)',
                'rgba(201, 203, 207, 0.5)',
                'rgba(255, 99, 132, 0.5)',
                'rgba(255, 159, 64, 0.5)',
                'rgba(255, 205, 86, 0.5)',
                'rgba(75, 192, 192, 0.5)'
            ],
        },
        {
            barPercentage: 1.0,
            order: 2,
            label: 'Bachelor Pension',
            data: [40,43,47,50,53,56,67,77,86,96,105,113,120,127,133,139,144,149,154,160,163],
            backgroundColor: [
                'rgba(255, 99, 132, 0.2)',
                'rgba(255, 159, 64, 0.2)',
                'rgba(255, 205, 86, 0.2)',
                'rgba(75, 192, 192, 0.2)',
                'rgba(54, 162, 235, 0.2)',
                'rgba(153, 102, 255, 0.2)',
                'rgba(201, 203, 207, 0.2)',
                'rgba(255, 99, 132, 0.2)',
                'rgba(255, 159, 64, 0.2)',
                'rgba(255, 205, 86, 0.2)',
                'rgba(75, 192, 192, 0.2)',
                'rgba(54, 162, 235, 0.2)',
                'rgba(153, 102, 255, 0.2)',
                'rgba(201, 203, 207, 0.2)',
                'rgba(255, 99, 132, 0.2)',
                'rgba(255, 159, 64, 0.2)',
                'rgba(255, 205, 86, 0.2)',
                'rgba(75, 192, 192, 0.2)',
                'rgba(54, 162, 235, 0.2)',
                'rgba(153, 102, 255, 0.2)',
                'rgba(201, 203, 207, 0.2)',
                'rgba(255, 99, 132, 0.2)',
                'rgba(255, 159, 64, 0.2)',
                'rgba(255, 205, 86, 0.2)',
                'rgba(75, 192, 192, 0.2)'
            ],
        },
      ]
    },
    options: {
        responsive: true,
        legend: {
            display: false,
        },
        scales: {
            x: { stacked: true },
            y: { stacked: true }
        }
    }
});
// Master
new Chart(document.getElementById("bar-chart-master"), {
    type: 'bar',
    data: {
      labels: ['2','3','4','5','6','7','8','9','10','11','12','13','14','15','16','17','18','19','20','21','22'],
      datasets: [
       {
            barPercentage: 1.0,
            order: 1,
            label: 'Master Salary',
            data: [619,669,722,765,706,848,890,929,968,1005,1041,1071,1103,1129,1155,1176,1196,1218,1238,1259,1272],
            backgroundColor: [
                'rgba(255, 99, 132, 0.5)',
                'rgba(255, 159, 64, 0.5)',
                'rgba(255, 205, 86, 0.5)',
                'rgba(75, 192, 192, 0.5)',
                'rgba(54, 162, 235, 0.5)',
                'rgba(153, 102, 255, 0.5)',
                'rgba(201, 203, 207, 0.5)',
                'rgba(255, 99, 132, 0.5)',
                'rgba(255, 159, 64, 0.5)',
                'rgba(255, 205, 86, 0.5)',
                'rgba(75, 192, 192, 0.5)',
                'rgba(54, 162, 235, 0.5)',
                'rgba(153, 102, 255, 0.5)',
                'rgba(201, 203, 207, 0.5)',
                'rgba(255, 99, 132, 0.5)',
                'rgba(255, 159, 64, 0.5)',
                'rgba(255, 205, 86, 0.5)',
                'rgba(75, 192, 192, 0.5)',
                'rgba(54, 162, 235, 0.5)',
                'rgba(153, 102, 255, 0.5)',
                'rgba(201, 203, 207, 0.5)',
                'rgba(255, 99, 132, 0.5)',
                'rgba(255, 159, 64, 0.5)',
                'rgba(255, 205, 86, 0.5)',
                'rgba(75, 192, 192, 0.5)'
            ],
        },
        {
            barPercentage: 1.0,
            order: 2,
            label: 'Master Pension',
            data: [43,47,51,54,59,70,80,90,100,109,118,126,134,140,147,152,157,163,168,173,176],
            backgroundColor: [
                'rgba(255, 99, 132, 0.2)',
                'rgba(255, 159, 64, 0.2)',
                'rgba(255, 205, 86, 0.2)',
                'rgba(75, 192, 192, 0.2)',
                'rgba(54, 162, 235, 0.2)',
                'rgba(153, 102, 255, 0.2)',
                'rgba(201, 203, 207, 0.2)',
                'rgba(255, 99, 132, 0.2)',
                'rgba(255, 159, 64, 0.2)',
                'rgba(255, 205, 86, 0.2)',
                'rgba(75, 192, 192, 0.2)',
                'rgba(54, 162, 235, 0.2)',
                'rgba(153, 102, 255, 0.2)',
                'rgba(201, 203, 207, 0.2)',
                'rgba(255, 99, 132, 0.2)',
                'rgba(255, 159, 64, 0.2)',
                'rgba(255, 205, 86, 0.2)',
                'rgba(75, 192, 192, 0.2)',
                'rgba(54, 162, 235, 0.2)',
                'rgba(153, 102, 255, 0.2)',
                'rgba(201, 203, 207, 0.2)',
                'rgba(255, 99, 132, 0.2)',
                'rgba(255, 159, 64, 0.2)',
                'rgba(255, 205, 86, 0.2)',
                'rgba(75, 192, 192, 0.2)'
            ],
        },
      ]
    },
    options: {
        responsive: true,
        legend: {
            display: false,
        },
        scales: {
            x: { stacked: true },
            y: { stacked: true }
        }
    }
});
</script>

The pay for each employee is adjusted according to this system every year, no additional process is required.

### Pension

TurtleSec pays the highest allowed amount for your pension ("innskuddspensjon"), measured in the [index regulated G value][3]

* 7% from 0 NOK to [7.1 G][3], *in 2022 this range is approx 0-791k NOK*
* 25.1% from [7.1 G][3] to [12 G][3], *in 2022 this range is approx 791k-1.34m NOK*

In addition to this the government pays an amount equivalent to 18.1% for salaries up to 7.1 G.

### Overtime

Overtime will probably not happen, but if it does it is calculated like this (+50% per hour)

```
(yearly salary (NOK) / 1950 (hours)) * 1.5 = overtime pay in NOK per hour
```

### Vacation

At TurtleSec we have 5 weeks vacation per year. In Norway an employer is required to save up for your vacation. This is done by saving an amount equivalent to 12% of your monthly salary every month. This is called "feriepenger" or vacation money. The normal thing is that this is paid out instead of salary in June the following year. There are many ways to structure when this is paid out and when you have your vacation, so discuss your needs with your manager.

Christmas Eve and New Years Eve are paid days off. We will naturally accommodate other religious holidays as needed.

### Sick Leave

We follow the rules for sick leave which are outlined in ["Inkluderende Arbeidsliv"][2] ("Inclusive Employment"), which is a government initiative to make workplaces more accessible:

* You can self-report illness ("egenmelding") for up to 8 consecutive days
* For up to a total of 24 days per each 12 month period
* You are entitled to paid time off for caring for sick children ("omsorgsdager") how many will depend on your family situation
* This "care leave" can also be self-reported
* You will receive your full salary during your self-reported illness or care leave
* For illnesses beyond the self-reporting days above, a doctor's note can be supplied
* For illnesses longer than 16 consecutive days, the state agency NAV will cover your salary up to 6 G (where a "G" is index regulated and in 2022 it is [111.477 NOK][3])

#### Notes on Sick Leave

* You can register your sick leave by the hour, if for example you need to go to a doctor or fell ill at work or if you work a few hours from home while ill
* Care leave ("omsorgsdager") can also be registered by the hour
* Mental health is also health, and self-reported sick leave can also be used for this
* If you have a temporary disability, permanent disability or a chronic illness we will work with you and NAV to accommodate your needs
* There are many details and laws in this area, so speak to your manager and we will work with you to make this as smooth as possible

### Moving Day

All employees get a paid day off when they move.

### Accessibility

The office itself is on the floor above the ground floor of an old building which does not have an elevator. We will try to accommodate any kind of disability including providing the necessary equipment adapted to individual needs and/or preferences.

### Parental leave

The Norwegian government will cover up to [6 G][3] of your pay during your parental leave (there are several important conditions here that you should research). How it can be split between the parents and how it can be paid out is [very flexible][4], high level summary: the full combined period is 49 weeks at 100% pay or 59 weeks at 80% pay split between the parents. The difference between your TurtleSec salary and the [6 G][3] limit will be covered by TurtleSec for up to 6 months provided that you have worked for TurtleSec for at least 6 months.

### Notice Period

As is the norm in Norway there are two different lengths of notice when one resigns, during your trial period this is customarily shorter. The short notice period during the trial period is mainly to allow the employee to change their mind. There are still strong protections against firings even in the trial period.

* Notice during trial period: 2 weeks
* Notice after trial period: 3 months starting from the first day of the following calendar month

#### Notes on Notice Period

* There are strict laws around termination of employment in Norway. It is as a rule very difficult to fire someone. This creates a work environment where people are not afraid to speak their minds, which we consider to be extremely valuable. 

### Remote

Usually we will work at the clients' offices, if the client permits we can also work remotely. How that is structured will depend on the client and the employee. We hope to have regular days where we work from the TurtleSec office so that we can get to know each other better.

### Travel

As a rule no travel is required, but if the employee has a client that requires travel, all travel, accommodation and meals will be covered by TurtleSec. A TurtleSec employee will not be required to take a client that requires travel.

### Language

All public-facing information at TurtleSec is as a rule in English, informal communication should be adapted to the recipient(s). Clients might require fluent English and/or Norwegian. TurtleSec will facilitate and pay for Norwegian classes if desired by the employee or required by a client.

### Tech Unions in Norway

Depending on ones level of education there are different options in Norway for unions.

- Masters: [Tekna][6]
- Masters and Bachelors: [NITO][7]
- All levels of eduaction: [EL og IT Forbundet][8]

Advantages often include support if one has a dispute with an employer and good deals on insurance.

<!--- TODO

### Insurance

### Relocation Assistance

## Norway

### Workers rights

#### Tax on income

#### Tax rebate for union fees

### Healthcare

### Childcare

#### Kindergarten

#### After school program

### Education

-->

[1]: https://www.tekna.no/lonn-og-arbeidsvilkar/lonnsstatistikk/
[2]: https://no.wikipedia.org/wiki/Inkluderende_arbeidsliv
[3]: https://www.nav.no/no/nav-og-samfunn/kontakt-nav/utbetalinger/grunnbelopet-i-folketrygden
[4]: https://familie.nav.no/om-foreldrepenger
[5]: https://www.nito.no/lonn-arbeidsliv-lonnskalkulator/
[6]: https://www.tekna.no
[7]: https://www.nito.no
[8]: https://elogit.no
