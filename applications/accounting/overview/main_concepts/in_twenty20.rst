:banner: banners/accounting.jpg

=====================================
Twenty20 Accounting Features
=====================================


Double-entry bookkeeping
========================

Twenty20 automatically creates all the behind-the-scenes journal entries
for each of your accounting transactions: customer and vendor invoices, payroll, expenses, inventory transfers, etc.

Twenty20 uses the rules of double-entry bookkeeping system: all journal
entries are automatically balanced (sum of debits = sum of credits).

.. seealso::

	`Understand Twenty20's Accounting Transactions </memento.html/>`__

Accrual and Cash Basis Methods
==============================

Twenty20 supports both accrual and cash basis reporting. This allows you to
report income / expense at the time transactions occur (i.e., accrual basis), or when
payment is made or received (i.e., cash basis).

Multi-companies
===============

Twenty20 allows you to manage several companies within the same database. Each
company has its own chart of accounts and rules. You can get
consolidation reports following your consolidation rules.

Users can access several companies, but always work in one company at a
time.

Multi-currencies
================

Every transaction is recorded in the default currency of the
company. For transactions occurring in another currency, Twenty20 stores
both the value in the currency of the company and the value in the
currency of the transaction. Twenty20 can generate currencies gains and
losses after the reconciliation of the journal items.

Currency rates are updated once a day using a yahoo.com online
web-service.

International Standards
=======================

Twenty20 accounting supports more than 50 countries. The Twenty20 core
accounting implements accounting standards that are common to all
countries. Specific modules exist per country for the
specificities of the country like the chart of accounts, taxes, or
bank interfaces.

In particular, Twenty20's core accounting engine supports:

* Anglo-Saxon Accounting (U.S., U.K., and other English-speaking
  countries including Ireland, Canada, Australia, and New Zealand)
  where costs of good sold are reported when products are
  sold/delivered.
* European accounting where expenses are accounted at the vendor
  invoice.
* Storno accounting (Italy) where refund invoices have negative
  credit/debit instead of a reversing entry for the original journal items.

Twenty20 also has modules to comply with IFRS rules.

Accounts Receivable & Payable
=============================

By default, Twenty20 uses a single account for all account
receivable entries and one for all accounts payable entries. You can
create separate accounts per customers/vendors, but you don't need
to.

As transactions are associated to customers or vendors, you get
reports to perform analysis per customer/vendor such as the customer
statement, revenues per customers, aged receivable/payables etc.

Wide range of financial reports
===============================

In Twenty20, you can generate financial reports in real time. Twenty20's
reports range from basic accounting reports to advanced management
reports. Twenty20's reports include:

* Performance reports (such as Profit and Loss, Budget Variance)
* Position reports (such as Balance Sheet, Aged Payables, Aged
  Receivables)
* Cash reports (such as Bank Summary)
* Detail reports (such as Trial Balance and General Ledger)
* Management reports (such as Budgets, Executive Summary)


Import bank feeds automatically
===============================

Bank reconciliation is a process that matches your bank statement
lines, as supplied by the bank, to your accounting transactions in the
general ledger. Twenty20 makes bank reconciliation easy by allowing you to
importing bank statement lines from your bank directly into your Twenty20
account. This means you can have a daily view of your cashflow without
having to log into your online banking or wait for your paper bank
statements.

Twenty20 speeds up bank reconciliation by matching most of your imported
bank statement lines to your accounting transactions. Twenty20 also
remembers how you've treated other bank statement lines and provides
suggested general ledger transactions.

Calculate the tax you owe your tax authority
============================================

Twenty20 totals all your accounting transactions for your tax period and
uses these totals to calculate your tax obligation. You can then check
your sales tax by running Twenty20's Tax Report.

Inventory Valuation
===================

Twenty20 support both periodic (manual) and perpetual (automated)
inventory valuations. The available methods are standard price,
average price, LIFO (for countries allowing it) and FIFO.

Easy retained earnings
======================

Retained earnings are the portion of income retained by your
business. Twenty20 automatically calculates your current year earnings in
real time so no year-end journal or rollover is required.  This is
calculated by reporting the profit and loss balance to your balance
sheet report automatically.
