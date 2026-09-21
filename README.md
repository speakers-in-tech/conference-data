## Tech Conference Data

This repository attempts to maintain comprehensive, high-quality data about tech conferences, focusing on their policies regarding the engagement of speakers, and in particular, whether or not organizers have indicated a willingness to stand up for the rights of speakers by signing the official [Speaker Engagement Agreement](https://github.com/speakers-in-tech/sea/blob/main/SEA.md).
More background on this initiative is contained in the blog post, [The Dark Side of Speaking at Tech Conferences](https://www.linkedin.com/pulse/dark-side-speaking-tech-conferences-john-de-goes/?trackingId=U6NAMEIvQr2LFDGbv4A4%2Fw%3D%3D). 

## Disclaimer

All information in this repository is provided on a _best-effort_ basis. If an organizer of any tech conference identifies inaccuracies in the data, please open an issue or pull request to correct the information.

## Data

The conference data is maintained in [conferences.csv](conferences.csv). Each row represents a conference with the following columns:

| Column | Description |
|--------|-------------|
| `name` | Name of the conference |
| `website` | URL of the conference website |
| `location` | Primary location of the conference |
| `country` | Country where the conference is held |
| `date` | Date or date range of the conference (YYYY-MM-DD or YYYY-MM-DD/YYYY-MM-DD) |
| `sea_signed` | Whether the conference has signed the Speaker Engagement Agreement (yes/no/unknown) |
| `notes` | Additional notes or context |

## Contributing

To add a new conference:

1. Open an issue with the conference name and basic details.
2. The maintainers will reach out to the conference organizers to ask about their policies.
3. If organizers refuse to answer questions, the conference is added with `sea_signed` set to `no` (assuming they are not willing to sign the SEA). This can be corrected later if the information proves inaccurate.
4. Submit a pull request updating `conferences.csv` with the new row.

## License

See [LICENSE](LICENSE) for details.
