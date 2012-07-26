SecurePort -- SSH portforward frontend
======================================

SecurePort is a small application to achieve SSH portforwarding.

Feature
-------

* Private key authentication (OpenSSH format is available).
* Multiple forwarding ports.

Limitation
----------

* Private keys that contain passphrase are not supported.
* Password authentication is not supported.
* Only one connection is supported by one instance.

License
-------

SecurePort is distributed under The MIT License (see LICENSE).

Acknowledgement
---------------

SecurePort uses the following packages to develop:

* Nemerle
   * Copyright (c) 2003-2008 The University of Wroclaw
   * Copyright (c) 2008-2011 Nemerle Project Team
* NUnit
   * Copyright (c) 2002-2012 Charlie Poole
   * Copyright (c) 2002-2004 James W. Newkirk, Michael C. Two, Alexei A. Vorontsov
   * Copyright (c) 2000-2002 Philip A. Craig
* SSH.NET Library
   * Copyright (c) 2010 RENCI

