+++

+++
# Etiket til vare - Ark 4 x 10

Navnet på denne rapport er: 'ItemLabel'. Vi opretter automatisk denne rapport i alle nye abonnementer.

> ![Eksempel på etiket til vare - Ark 4 x 10](https://thetis-ims-reports.s3.eu-west-1.amazonaws.com/examples/ItemLabel-1.png)

Hver etiket indeholder en stregkode med varens [GTIN](https://data.thetis-ims.com/da/docs/GlobalTradeItem#globalTradeItemNumber "GTIN"). Indkodningen er afhængig af længden af varens GTIN:

* 13 cifre: EAN-13
* 12 cifre: UPC-A
* 8 cifre: EAN-8
* Alle andre længder: Code-128

Bemærk, at hvis længden af GTIN er 13, 12 eller 8, så skal varens GTIN være validt. Det vil blandt andet sige, at checkcifferet i nummeret skal være korrekt. Hvis dette ikke er tilfældet, vil rapporten ikke vise nogen stregkode for varen.

Du kan downloade eksemplet her: [ItemLabel.pdf](https://thetis-ims-reports.s3.eu-west-1.amazonaws.com/examples/ItemLabel.pdf "ItemLabel.pdf")