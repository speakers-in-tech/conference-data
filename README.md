## Tech Conference Data

This repository attempts to maintain comprehensive, high-quality data about tech conferences, focusing on their policies regarding the engagement of speakers, and in particular, whether or not organizers have indicated a willingness to stand up for the rights of speakers by signing the official [Speaker Engagement Agreement](https://github.com/speakers-in-tech/sea/blob/main/SEA.md).
More background on this initiative is contained in the blog post, [The Dark Side of Speaking at Tech Conferences](https://www.linkedin.com/pulse/dark-side-speaking-tech-conferences-john-de-goes/?trackingId=U6NAMEIvQr2LFDGbv4A4%2Fw%3D%3D). 

## Disclaimer

All information in this repository is provided on a _best-effort_ basis. If an organizer of any tech conference identifies inaccuracies in the data provided, then we encourage them to submit a pull request to the repository.

**Note on Disputes**: In the event of disputes between an organizer's stated policies and speakers' experience with this event, we will note both the organizer's stated policies, as well as the experience of speakers.

## Interpreting the Data

The conference dataset hosted in this repository tracks the following information:

1. **Conference**. The conference column lists the name of some tech conference, and links to the event's primary home page. If the event does not have a primary home page, because the website is seasonal, then the event name may link to the organizer of the conference.
2. **Organizer**. The organizer column lists the organizer of the tech conference. In most cases, this is an organization. In some cases, it may be an individual. In cases where it is a partnership of individuals, the name will either link to one individual (a public primary organizer), or none at all (in the event there is no public primary organizer).
3. **SEA**. _SEA_ stands for _Speaker Engagement Agreement_, and refers to the [Speaker Engagement Agreement](https://github.com/speakers-in-tech/sea/blob/main/SEA.md), a legally binding contract between speaker and organizer that sets out the terms and conditions of a speaking engagement. The SEA has strong provisions to protect the rights of speakers, ensuring they are not mistreated or abused. If an organizer is known to be willing to sign the SEA upon request, then you will find a `Yes` in this column. Otherwise, you will find a `No` (if the organizer refuses to sign the SEA), `Varies` (if the event is a composite event, each of which is run by different organizers), or `Pending` if the organizer's legal team needs to review SEA.
4. **Free Ticket**. This column tracks whether a tech conference provides speakers with a free ticket. The vast majority of tech conferences provide speakers with a free ticket, but some events require speakers to pay for tickets, in the same fashion as attendees.
5. **Reimburse Expenses**. This column tracks whether a tech conference is known to reimburse speakers for their travel expenses involved in speaking at a conference. The possible values are `Full`, `Partial`, and `No`. Note that hotel accommodations are considered a form of partial reimbursement. Full reimbursement would include travel to and from the event, as well as hotel accommodations, and a per diem for food and beverages.
6. **Compensate Speakers**. This column tracks whether a tech conference is known to pay speakers for their engagements. The possible values are `Never` or the category of presentation the event reimburses for. Most tech conferences do not compensate speakers for standard-length talks, although a few provide compensation for keynotes or workshops or other sessions of extended duration.

  
## Conference Dataset
  
| Conference | Organizer | Sign SEA? | Free Ticket? | Reimburse Expenses? | Compensate Speakers? |  
|------------|-----------|-----------|--------------|---------------------|----------------------|  
| [Code Europe](https://www.codeeurope.pl/en/) | [Absolvent](https://www.absolvent.pl/informacje/o-nas#/) | Yes | Yes | Yes | Never |
| [Functional Scala](https://functionalscala.com) | [Ziverge](https://ziverge.com) | Yes | Yes | Partial | Never |
| [LambdaConf](https://lambdaconf.us) | [Ziverge](https://ziverge.com) | Yes | Yes | Partial | Workshops |
| [ZIO World](https://zioworld.com) | [Ziverge](https://ziverge.com) | Yes | Yes | No | Never |
| [ScalarConf](https://www.scalar-conf.com) | [Software Mill](https://softwaremill.com/) | No | Yes | No | Never | 
| [PyCon](https://pycon.org) | PyCon Board Committee | Pending | No | Yes | Keynote |
| [JSConf](https://jsconf.com/) | Local Community | Varies | Yes | Partial | Yes | 
| [NESCALA](https://github.com/nescalas/nescalas.github.io) | Volunteers | No | Partial | No | Never | 
| [Øredev](https://oredev.org/) | [Öredev AB](https://oredev.org) | No | No | No | Never | 
| [Lambda World](https://www.lambda.world/) | [Xebia Functional](https://www.47deg.com/) | Yes | No | Yes | Never | 
| [GOTO](https://gotopia.tech/) | [Trifork](https://trifork.com/) | Yes | No | Reasonable  | Never | 
| [CodeMash](https://codemash.org/) | [CodeMash Team](https://codemash.org/organizers/) | Yes | Yes | Yes | Yes |


## Contributing

We welcome new data into this open-source dataset! Please reach out to the organizers of tech conferences inside your own community or domain, and ask them the following questions:

1. What is the conference, and the primary link to the conference?
2. Who organizes the conference, and what is the primary link to the organizer?
3. Is the organizer willing to sign the [Speaker Engagement Agreement](https://github.com/speakers-in-tech/sea/blob/main/SEA.md) for each speaker who so requests?
4. Does the organizer provide a free ticket to speakers of the event?
5. To what extent will the organizer reimburse a speaker for expenses incurred in traveling to and delivering a talk?
6. In what circumstances would the organizer compensate speaker for their talk?

If you want to amend or add information to the table, please follow these steps:  
  
4. Fork the `speakers-in-tech/conference-data` repository on Github.com.  
5. Make changes to the `README.md` file using Markdown syntax.  
6. Ensure that the changes are consistent with the existing format of the table, and that you insert data for new conferences alphabetically by conference name.
7. Save your changes and submit a pull request with a brief explanation of the changes you made.  
8. If you are not the organizer, please explain how you acquired the information you are adding to the table.
9. Once your pull request is reviewed and merged, the changes will be updated to the main branch of the repository.  
