+++

+++
# Følgeseddel - A4 grupperet efter forsendelsesbeholder

Navnet på denne rapport er: 'DeliveryNote'. Du skal selv oprette denne rapport, hvis du ønsker at bruge den. 

> ![](https://thetis-ims-reports.s3.eu-west-1.amazonaws.com/examples/DeliveryNote_da-1.png)

Rapporten viser de varer, som er pakket til en forsendelse. Varerne er grupperet efter forsendelsesbeholder.

Det er kun muligt at bruge denne rapport på forsendelser, hvor varerne er pakket i forsendelsesbeholdere. Rapporten vil ikke vise varer, som ikke er pakket i forsendelsesbeholdere.

Rapporten viser et varenummer. Værdien af varenummeret afhænger imidlertid af, hvilken information der er til rådighed. Hvis [kundens varenummer](https://data.thetis-ims.com/da/docs/ShipmentLine#customersItemNumber "Kundens varenummer") er kendt, bruger rapporten værdien fra dette felt. Ellers hvis [varens branchenummer ](https://data.thetis-ims.com/da/docs/GlobalTradeItem#businessItemNumber "Varens branchenummer")er kendt, så bruger systemet værdien derfra. Hvis heller ikke dette er kendt, så bruger rapporten vores SKU som varenummer.

Du kan downloade eksemplet her: [DeliveryNote.pdf](https://thetis-ims-reports.s3.eu-west-1.amazonaws.com/examples/DeliveryNote.pdf "DeliveryNote.pdf")