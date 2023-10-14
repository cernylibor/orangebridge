
As the whole play is intended for Armbian, no checks such as
     when: ansible_distribution == "Debian"
are being made. This play will hence fail on non-Debian distributions.
