
LearnerFlow Backend
===================

This custom version of the Hypothesis Server has been adapted from the original [`hypothesis/h`](https://github.com/hypothesis/h) to include several enhancements:

We included provision to manage and store data pertaining to the following enhancements:

1. **New Granular Tagging Categories**: We've introduced additional tagging categories, including "Comment," "Important," "Errata," "Interesting," "Confusing," and "Question." These tags allow for more precise annotation categorization.

2. **Upvote Feature**: We've added an upvote feature for posts, providing users with the ability to endorse annotations or comments.

3. **Enhanced Analytics**: Our customized client includes enhanced analytics capabilities that track every click, keypress, and scroll on the page. This feature provides valuable insights into user interactions and behaviors within the platform.

4. **Course Metadata**: Our customized databased includes enhancements to store information such as:
 - Course Information : offering dates (start/end), Campus, number of assessments
 - Assessment & Student Demographics Infomation: This can either be imported into the database or handled within just the dashboard  boweser through csv import


Feel free to explore these enhancements and provide feedback on their functionality.



h
=

.. image:: https://travis-ci.org/hypothesis/h.svg?branch=master
   :target: https://travis-ci.org/hypothesis/h
   :alt: Build Status
.. image:: https://codecov.io/github/hypothesis/h/coverage.svg?branch=master
   :target: https://codecov.io/github/hypothesis/h?branch=master
   :alt: Code Coverage
.. image:: https://img.shields.io/badge/IRC-%23hypothes.is-blue.svg
   :target: `#hypothes.is`_
   :alt: #hypothes.is IRC channel
.. image:: https://img.shields.io/badge/license-BSD-blue.svg
   :target: https://github.com/hypothesis/h/blob/master/LICENSE
   :alt: License badge
.. image:: https://img.shields.io/badge/python-2.7-blue.svg
   :alt: Python version badge

h is the web app that serves most of the https://hypothes.is/ website,
including the web annotations API at https://hypothes.is/api/.
The `Hypothesis client <https://github.com/hypothesis/client>`_
is a browser-based annotator that is a client for h's API.


Development
-----------

See the `Contributor's guide`_ for instructions on setting up a development
environment and contributing to h.


Community
---------

Join us on Slack (`request an invite`_ or `log in once you've created an account`_) or in `#hypothes.is`_ on freenode_ for discussion.

If you'd like to contribute to the project, you should also `subscribe`_ to the
`development mailing list`_ and read our `Contributor's guide`_. Then consider
getting started on one of the issues that are ready for work.

Please note that this project is released with a Contributor Code of Conduct.
By participating in this project you agree to abide by its terms.

.. _`request an invite`: https://slack.hypothes.is
.. _`log in once you've created an account`: https://hypothesis-open.slack.com/
.. _#hypothes.is: https://www.irccloud.com/invite?channel=%23hypothes.is&amp;hostname=irc.freenode.net&amp;port=6667&amp;ssl=1
.. _freenode: http://freenode.net/
.. _subscribe: mailto:dev+subscribe@list.hypothes.is
.. _development mailing list: https://groups.google.com/a/list.hypothes.is/forum/#!forum/dev
.. _Contributor's guide: https://h.readthedocs.io/en/latest/developing/


License
-------

Hypothesis is released under the `2-Clause BSD License`_, sometimes referred
to as the "Simplified BSD License" or the "FreeBSD License". Some third-party
components are included. They are subject to their own licenses. All of the
license information can be found in the included `<LICENSE>`_ file.

.. _2-Clause BSD License: http://www.opensource.org/licenses/BSD-2-Clause
