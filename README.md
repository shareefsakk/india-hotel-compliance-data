# india-hotel-compliance-data

Small, sourced, machine-readable data on the rules Indian hotels, hostels and homestays deal with every day. Every entry names its source and the date we checked it. Where we have not yet verified an official URL for the rule itself, the file says so.

Maintained by [GuestHawk](https://guesthawk.com). If you want the calculators rather than the data, use the free tools at **[guesthawk.com/tools](https://guesthawk.com/tools)**: no sign-up, and nothing you type leaves your browser.

## Files

| File | What it holds |
|---|---|
| `data/gst-hotel-rooms.json` | GST on hotel rooms (5% up to ₹7,500 per unit per night without ITC; 18% above with ITC; tested per room per night; since 22 Sep 2025) and on restaurants (5%, or 18% in specified premises) |
| `data/form-iii.json` | Form-III (formerly Form C): every foreign guest reported online within 24 hours of arrival, under the Immigration and Foreigners Act, 2025, on indianfrro.gov.in |
| `data/state-homestay-links.json` | Official homestay scheme pages for four states (Goa, Karnataka, Kerala, Uttarakhand) |

We keep the data small on purpose. A state appears only when its official page answered on the checked date and said what we list. A missing state means we have not verified it yet. It does not mean there is no scheme.

## Sources

- PIB, FAQs on the decisions of the 56th GST Council: https://www.pib.gov.in/PressReleasePage.aspx?PRID=2167151
- GST Council, press release on the 56th meeting recommendations: https://gstcouncil.gov.in/sites/default/files/2025-09/press_release_press_information_bureau_0.pdf
- Notification 05/2025-Central Tax (Rate), the definition of specified premises: https://gstcouncil.gov.in/sites/default/files/2025-01/ctr05-2025.pdf
- Bureau of Immigration, Online Form III filing portal: https://indianfrro.gov.in/frro/FormC (the filing route; the 24-hour rule is in the Immigration and Foreigners Act, 2025, official text URL not yet verified)
- State tourism department pages, listed per entry in `data/state-homestay-links.json`

Plain-English explanations, with worked examples, are in the GuestHawk guides:

- [GST on hotel rooms and restaurants](https://guesthawk.com/guides/gst-on-hotel-rooms-and-restaurants)
- [Form-III for hotels](https://guesthawk.com/guides/form-iii-for-hotels)
- [Homestay registration in India](https://guesthawk.com/guides/homestay-registration-in-india)

## Not advice

This is general information as of the `as_of` date in each file. It is not tax or legal advice. Confirm your own case with your chartered accountant, your FRRO or your state tourism department.

## Corrections

If a rule changes or a link breaks, open an issue with the official source. We fix the data first, then the guides and calculators.

## License

The data in `data/` is licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). You may share and adapt it, including commercially, with credit:

> Source: GuestHawk, india-hotel-compliance-data (https://guesthawk.com/tools)

The rules themselves come from Government of India and state government publications. The licence covers our compilation and structure.
