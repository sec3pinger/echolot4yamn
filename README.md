# echolot4yamn
Echolot For YAMN Remailers

Echolot was written by Peter Palfrader. In its original form it
was a pinger program for Mixmaster and Cpunk remailers.

In this repo it has been hacked to make it work with the new YAMN
anonymous remailers.

A Pinger in the context of anonymous remailers is a program that
regularly sends messages through remailers to determine their status.
Based on the responses, the Pinger calculates reliability statistics
which may be used by remailer clients to choose a chain of remailers to
use.

Furthermore, Echolot collects configuration parameters and keys of
remailers and offers the collected information in a format readable by
remailer clients. This helps reduce the administration effort required
to use or host remailers.

Visit <https://sac001.github.io/yamnhelp/install_yamn_pinger.html> for
a step-by-step guide on how to set up an Echolot YAMN pinger service.
