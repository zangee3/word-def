# Word Definitions API

### Dictionary Provider
Oxford Dictionaries : http://oxforddictionaries.com


### Usage

Simply call the API: https://word-def.herokuapp.com/api/[word]
to get a list of definitions.

## Sample Request

https://word-def.herokuapp.com/api/arbitrary

Results:
```
{
"defs": {
"metadata": {
"provider": "Oxford University Press"
},
"results": [
{
"id": "arbitrary",
"language": "en",
"lexicalEntries": [
{
"entries": [
{
"etymologies": [
"late Middle English (in the sense ‘dependent on one's will or pleasure, discretionary’): from Latin arbitrarius, from arbiter ‘judge, supreme ruler’, perhaps influenced by French arbitraire"
],
"grammaticalFeatures": [
{
"text": "Positive",
"type": "Degree"
}
],
"homographNumber": "000",
"senses": [
{
"definitions": [
"based on random choice or personal whim, rather than any reason or system"
],
"examples": [
{
"text": "an arbitrary decision"
}
],
"id": "m_en_gbus0044300.006"
},
{
"definitions": [
"(of power or a ruling body) unrestrained and autocratic in the use of authority"
],
"examples": [
{
"text": "a country under arbitrary government"
}
],
"id": "m_en_gbus0044300.009"
},
{
"definitions": [
"(of a constant or other quantity) of unspecified value."
],
"domains": [
"Mathematics"
],
"id": "m_en_gbus0044300.011"
}
]
}
],
"language": "en",
"lexicalCategory": "Adjective",
"pronunciations": [
{
"audioFile": "http://audio.oxforddictionaries.com/en/mp3/arbitrary_gb_1.mp3",
"dialects": [
"British English"
],
"phoneticNotation": "IPA",
"phoneticSpelling": "ˈɑːbɪt(rə)ri"
}
],
"text": "arbitrary"
}
],
"type": "headword",
"word": "arbitrary"
}
]
}
}
```

