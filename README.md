# Techmap certificates

<img width="516" alt="Screenshot 2021-11-30 at 14 05 26" src="https://user-images.githubusercontent.com/1960230/144061757-01324ab3-e93a-462f-b608-f6e9e1e0006c.png">

Generate completion certificates for Techmap using a Photoshop template.

## Process

One day this'll be nicely-integrated with Graph and run in the Cloud, maybe using the Photoshop API. Till then, here's the process:

1. Make a CSV of the names you want to generate certificates for. Use this format:

```csv
name
Richard Sims
Tommmy Wiseau
Mr Peevis Butler
```


2. Open the template in Photoshop. (It's in ./template)
3. Go to "Image => Variables => Data Sets..."
4. Import the CSV you created as Data Sets
5. Go to "File => Export => Data Sets as Files..."
6. Save the files to a subdirectory in the Whatever Dropbox.
7. Convert the files from PSD to PNG (e.g. using [this service](https://cloudconvert.com/psd-to-png))
8. Send the certificates to the people.

## Showing certificates on LinkedIn

<img width="762" alt="Screenshot 2021-11-30 at 14 02 09" src="https://user-images.githubusercontent.com/1960230/144061268-df647a01-a7b1-4781-921c-dc4b52052cad.png">

People can add credentials on LinkedIn by going to "Edit my Profile". Or, they can follow this link:

https://www.linkedin.com/profile/add?startTask=CERTIFICATION_NAME&name=Techmap%20certified&organizationId=70420884&issueYear=2021

> If you host the PNG certificate somewhere with a publicly-accessible URL, participants can upload the certificate too! Or, they can just add https://techmap.app as the link.

