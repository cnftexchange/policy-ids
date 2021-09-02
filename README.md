# policy-ids

List of verified CNFTs policy ids.

## How to add your policy

1. Fork this repository
2. Add a file with the name of your project, in lowercase and using snake casing, i.e. `cardinos.json`
3. The file must be in JSON format as stated below:

```json
{
    "project": "Cardinos",
    "logo_url": "https://cardinos.io/static/assets/img/logo.png",
    "about": "Cardinos were born from a late night conversation about how simply awesome Dinosaurs and NFTs are.",
    "social_media": {
        "twitter": "CardinosNFT",
        "discord": "discord.gg/8peMhtCmqw",
        "website": "cardinos.io"
    },
    "tags": [
        "Cardinos", "Skydinos", "Seadinos"
    ],
    "policies": [
        "4a7f6db810294738dae82fdb201230f32ac18c0640d02fa0100756c0", 
        "56af1016943d18a253c7e2eff9e48dc7c39c977181b8ccb0d8b9b0b2", 
        "010aa7bbd3ccbf5090dca56c59e2b0179f5d8fabbbee5bd002a655df"
    ]
}

```
NOTE: If you have any questions just reach out to one of our developers.

## Approval procedure

A team member of `cnft.exchange` will contact you by the provided social media accounts to verify your request and identity. This generally happens in the next 24hs after you send the pull request.