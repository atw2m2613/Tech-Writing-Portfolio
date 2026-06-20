# Invoicing Warranty Pick Tickets

## Step One: Verify Received Pick Ticket

Verify the ticket for the following from the keyer:
 * Warranty Ticket Number
 * Freight Billing Instructions

If the billing instructions advise:
 * Bill servicer for freight, look for billable account number and freight costs
 * Servicer to pay in full, look for freight costs
 * Bill freight to the branch, no additional information is needed

Verify the ticket for the following items from the picker:
 * Parts confirmation & initials with date
 * Tracking information
 * Serial numbers for all serialized items, if applicable

If any applicable items are missing or unclear, escalate to appropriate team member:
 * Billable account numbers would be the responsibility of the keyer to note
 * Freight costs would be the responsibility of the picker to note
 * When in doubt, touch base with the keyer first

Once all items are verified, if billing instructions advise:
 * Bill freight to the servicer, proceed to Step Two
 * Servicer to pay in full, proceed to Step Three (ensure you fully read the "IF APPLICABLE, ADD FREIGHT COSTS" section)
 * Bill freight to the branch, proceed to Step Three

---

## Step Two: Keying Freight to Servicer Account

Follow the steps outlined in "Keying an Order," (not included in this document) using the following information:

  * Ship To: Billable account from Step One
  * Sales & Source Location: Set to the branch where the part is shipping from

        Ensure both locations match prior to putting in the part number, otherwise
        the system will lock you out and you'll have to restart the order.
  * Part Number: FRT
  * Quantity: 1
  * Unit Cost: Freight cost from Step One
  * Purchase Order: HOMEOWNER'S NAME - WTY FRT

        EX: JOHN SMITH - WTY FRT
  * Order Notes: BLEVINS TICKET #[ticket number] (the warranty ticket number from Step One) <br>
      FRT FOR WARRANTY ORDER #[order number]

        EX: BLEVINS TICKET #WAR-000123
            FRT FOR WARRANTY ORDER #12340699
Review all items to ensure completion and accuracy, then do the following:
  * Go to "Print Options"
  * Select "Print" under the "Invoice" segment
  * Select "Save" at the top of the order

The system will then generate a printable PDF document:
  * Print a physical copy
  * Save a digital copy: WAR[ticket number] INV [invoice number] - FRT

        EX: WAR123 INV 55533212 - FRT
Once complete, proceed to Step Three.

---

## Step Three: Processing the Invoice

Navigate to the "SHIPPING" screen in the Company EPR and perform the following:
 * In the 'PICK TICKET' field, input the pick ticket on the top of the ticket being processed & enter
 * Confirm if any additional information is required, if so, review the applicable step below:
    * Adding freight (if applicable)
       * Select the last line item under the "ORDER LINE ITEMS" section and hit tab until a new line appears
       * Part Number: FRT
       * Quantity: 1
       * Under the "PRICING" tab, Unit Cost: Freight cost from Step One
    * Adding the serial number for serialized items (if applicable)
       * Select the serialized item under the "ORDER LINE ITEMS" section
       * Under the "SERIAL" tab, key in the serial number from Step One and hit enter
       * The system will automatically select "ALLOCATE" - no changes are needed
 * Review that all necessary items have been added.
 * Select "Confirm Shipment" and then "Print"
 * Select "Save" at the top of the shipping screen

The system will then generate a printable PDF document:
  * Print a physical copy
  * Save a digital copy: WAR[ticket number] INV [invoice number]

        EX: WAR123 INV 55533213
Once complete, proceed to Step Four.

---

## Step Four: Information & Document Management

First, upload all notes and invoices associated with the order into it's related ticket following the steps outlined in "Ticket Uploads & Maintenance" (not included in this document).

Second, send tracking and relevant invoices to the servicer using the existing correspondance. Relevant invoices are freight invoices put on servicer accounts and invoices where the servicer paid in full (part only or part & freight).

File the physical copy per Company policy. 

Once all applicable steps are completed, you are finished with that ticket.
