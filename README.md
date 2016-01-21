# Adzerk

Ruby wrapper for the [Adzerk API](http://adzerk.com/).

## Installation

    sudo gem install adzerk

## Get your API key

Be sure and get your API key. Log into the management application at [http://manage.adzerk.net/](http://manage.adzerk.net/). Then, click on the settings tab, followed by the API Keys tab.

## Usage

Refer to the [https://github.com/adzerk/adzerk-api/wiki](https://github.com/adzerk/adzerk-api/wiki) of this repository for the properties needed for update and create.

### Examples

    require 'adzerk'
    client = Adzerk.new('your_api_key')
    client.Site.new.list


Copyright © 2011-2016 Adzerk, Inc.
