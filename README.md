# Phauxth

[![Patreon](https://img.shields.io/badge/patreon-donate-brightgreen.svg)](https://www.patreon.com/riverrun)
[![Hex.pm Version](http://img.shields.io/hexpm/v/phauxth.svg)](https://hex.pm/packages/phauxth)
[![Build Status](https://travis-ci.org/riverrun/phauxth.svg?branch=master)](https://travis-ci.org/riverrun/phauxth)

Phauxth is an authentication library for Phoenix, and other Plug-based,
web applications. It is designed to be secure, extensible, easy to use
and well-documented.

For a general overview of some of the goals of Phauxth and its basic usage,
see [this post](https://riverrun.github.io/projects/phauxth/2017/09/25/phauxth.html).

## Getting started

[This guide](https://github.com/riverrun/phauxth/wiki/Getting-started)
shows how you can set up a new Phoenix project with Phauxth.

## Authentication and authorization

The core Phauxth library handles authentication, verifying who the
user is.

For information about authorization, or access control, see the
[Authorization](https://github.com/riverrun/phauxth/wiki/Authorization) page
in the wiki.

If you have set up your app using the [Phauxth installer](https://github.com/riverrun/phauxth_installer),
the `authorize.ex` file in the controllers directory provides examples
of functions you can use to authorize users' access to resources.

## Example apps using Phauxth

* [A basic example](https://github.com/riverrun/phauxth-example) of using
Phauxth with email confirmation.
* [An example api](https://github.com/riverrun/phoenix-todoapp) using Phauxth.

## Contributing

There are many ways you can contribute to the development of Phauxth, including:

* reporting issues
* improving documentation
* sharing your experiences with others
* [making a financial contribution](#donations)

## Donations

You can support the ongoing maintenance of this project by
[making donations through Patreon](https://www.patreon.com/riverrun).

Patreon, by default, will bill you on a monthly basis. If you prefer to make a one-off payment,
see [this guide](https://support.patreon.com/hc/en-us/articles/204606215-Can-I-make-a-one-time-payment-).

### License

BSD
