# Dollatcoin

http://zebronix.com

What is Dollatcoin?

Dollatcoin is an experimental digital currency that enables instant payments to anyone, anywhere in the world. Dollatcoin uses peer-to-peer technology to operate with no central authority: managing transactions and issuing money are carried out collectively by the network. Dollatcoin Core is the name of open source software which enables the use of this currency.

For more information, as well as an immediately useable, binary version of the Dollatcoin Core software, see http://zebronix.com/.

License

Dollatcoin Core is released under the terms of license. See COPYING for more information or see http://zebronix.com/licenses/.

Development Process

The master branch is regularly built and tested, but is not guaranteed to be completely stable. Tags are created regularly to indicate new official, stable release versions of Dollatcoin Core.

The contribution workflow is described in CONTRIBUTING.md.

The developer mailing list should be used to discuss complicated or controversial changes before working on a patch set.

Developer IRC can be found on Freenode at #Dollatcoin-dev.

Testing

Testing and code review is the bottleneck for development; we get more pull requests than we can review and test on short notice. Please be patient and help out by testing other people's pull requests, and remember this is a security-critical project where any mistake might cost people lots of money.

Automated Testing

Developers are strongly encouraged to write unit tests for new code, and to submit new unit tests for old code. Unit tests can be compiled and run (assuming they weren't disabled in configure) with: make check

There are also regression and integration tests of the RPC interface, written in Python, that are run automatically on the build server. These tests can be run (if the test dependencies are installed) with: qa/pull-tester/rpc-tests.py

The Travis CI system makes sure that every pull request is built for Windows, Linux, and OS X, and that unit/sanity tests are run automatically.

Manual Quality Assurance (QA) Testing

Changes should be tested by somebody other than the developer who wrote the code. This is especially important for large or high-risk changes. It is useful to add a test plan to the pull request description if testing the changes is not straightforward.

Translations

We only accept translation fixes that are submitted through Bitcoin Core's Transifex page. Translations are converted to Dollatcoin periodically.

Translations are periodically pulled from Transifex and merged into the git repository. See the translation process for details on how this works.

Important: We do not accept translation changes as GitHub pull requests because the next pull from Transifex would automatically overwrite them again.
