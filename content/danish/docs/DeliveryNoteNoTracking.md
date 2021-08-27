+++

+++
# Følgeseddel - A4 Standard

Navnet på denne rapport er: 'DeliveryNoteNoTracking'. Vi opretter automatisk denne rapport i alle nye abonnementer.

> ![Eksempel på følgeseddel - A4 Standard](https://thetis-ims-reports.s3.eu-west-1.amazonaws.com/examples/DeliveryNoteNoTracking-1.png)

Rapporten viser de pakkede varer grupperet efter forsendelseslinje.

Rapporten viser et varenummer. Værdien af varenummeret afhænger imidlertid af, hvilken information der er til rådighed. Hvis [kundens varenummer](https://data.thetis-ims.com/da/docs/ShipmentLine#customersItemNumber "Kundens varenummer") er kendt, bruger rapporten værdien fra dette felt. Ellers hvis [varens branchenummer ](https://data.thetis-ims.com/da/docs/GlobalTradeItem#businessItemNumber "Varens branchenummer")er kendt, så bruger systemet værdien derfra. Hvis heller ikke dette er kendt, så bruger rapporten vores SKU som varenummer.

Du kan downloade eksemplet her: [DeliveryNoteNoTracking.pdf](https://thetis-ims-reports.s3.eu-west-1.amazonaws.com/examples/DeliveryNoteNoTracking.pdf "DeliveryNoteNoTracking.pdf")