# PeptideMinerAdvanced

`PeptideMinerAdvanced` нь PubMed-ээс self-assembling peptide-тэй холбоотой өгүүллүүдийн abstract татаж, SpaCy NLP болон regex pattern ашиглан peptide sequence, secondary structure, nanostructure, туршилтын нөхцөлүүдийг автоматаар илрүүлдэг Python text mining tool юм.

## Үндсэн боломжууд

- PubMed API ашиглан өгүүллийн PMID хайх
- PMID ашиглан өгүүллийн title болон abstract татах
- Peptide/amino acid sequence илрүүлэх
- Sequence бүрийн confidence score тооцоолох
- Hydrophobic, charged, aromatic amino acid composition шинжлэх
- Secondary structure илрүүлэх  
  Жишээ нь: beta-sheet, alpha-helix, random coil
- Nanostructure keyword илрүүлэх  
  Жишээ нь: nanofiber, hydrogel, nanotube, fibril
- Туршилтын нөхцөлүүдийг extract хийх  
  Жишээ нь: pH, temperature, salt, buffer, concentration
- Үр дүнг CSV файлд хадгалах

## Ашигласан технологи

- Python
- SpaCy
- Requests
- PubMed E-utilities API
- Regex
- CSV
- XML parsing

## Суулгах заавар

Эхлээд шаардлагатай сангуудыг суулгана.

```bash
pip install requests spacy
