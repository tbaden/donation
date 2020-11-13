[ This file must be present and contains the usage instructions
  for end-users. As all other rst files included in the README,
  it MUST NOT contain reStructuredText sections
  only body text (paragraphs, lists, tables, etc). Should you need
  a more elaborate structure to explain the addon, please create a
  Sphinx documentation (which may include this file as a "quick start"
  section). ]

After defining tax receipt options for membership products and members, start the memberhip buying process on partner level. 
Select a membership product wich has the 'eligible for tax receipt' option set to true and finish the buying process by 
confirming the invoice. 

Creating a payment for the invoice or reconciling it with a bank journal entry will set the status 'tax_receipt_ok' for the generation of a tax receipt. 
If the tax receipt configuration in the partner is set to for each donatoin, the tax receipt will be generated right away. In case of 
an annual receipt the membership fee will be added to the donation line on the annual receipt when it is created.

In case that a membership invoice is refunded or canceld in any way, the status 'tax receip ok' will be reversed. In case that a tax receipt has been 
created and is still in draft mode. The receipt or the donation line on the annual receipt will be deleted. If the receipt has been send to the recipient 
already, a notification will be set on the tax receipt.