# Newsletter Unsubscribe

## What does it do?

Extends Magento by a new Block to unsubscribe from the Newsletter - by default Magento allows Unsubscription only for logged in users, not for guests. 

Additionally, the module adds a frontend route to unsubscribe via dynamic link from within newsletters via shopdomain.tld/newsletter/unsubscribe/?email=alias@domain.tld


## How to use?

Example call via CMS Page:

	{{block type="sota_newsletter_unsubscribe/unsubscribe" name="newsletter.unsubscribe" template="newsletter/unsubscribe.phtml"}}

Example call via Layout Update:

	<block type="sota_newsletter_unsubscribe/unsubscribe" name="newsletter.unsubscribe" after="newsletter" template="newsletter/unsubscribe.phtml"/>


## Dependencies

* Mage_Newsletter