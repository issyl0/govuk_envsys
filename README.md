`govuk_envsys`
==============

This module manages `/etc/environment` in addition to the stock entries like
`PATH` and `LC_ALL`.

This is extracted from
https://github.com/alphagov/govuk-puppet/blob/master/modules/govuk_envsys/ to
try making it standalone with Test Kitchens, InSpec and be able to be tested
against Puppet 5 on Travis CI.
