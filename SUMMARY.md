<!--- @file
  First Chapter of EDK II Template Specification

  Copyright (c) 2017, Intel Corporation. All rights reserved.<BR>

  Redistribution and use in source (original document form) and 'compiled'
  forms (converted to PDF, epub, HTML and other formats) with or without
  modification, are permitted provided that the following conditions are met:

  1) Redistributions of source code (original document form) must retain the
     above copyright notice, this list of conditions and the following
     disclaimer as the first lines of this file unmodified.

  2) Redistributions in compiled form (transformed to other DTDs, converted to
     PDF, epub, HTML and other formats) must reproduce the above copyright
     notice, this list of conditions and the following disclaimer in the
     documentation and/or other materials provided with the distribution.

  THIS DOCUMENTATION IS PROVIDED BY TIANOCORE PROJECT "AS IS" AND ANY EXPRESS OR
  IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF
  MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO
  EVENT SHALL TIANOCORE PROJECT  BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
  SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO,
  PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS;
  OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY,
  WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR
  OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS DOCUMENTATION, EVEN IF
  ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

-->



# Summary

* [Getting Started with UEFI HTTPS Boot on EDK II](README.md)
* [Introduction](introduction/README.md)
  * [Overview](introduction/README.md#overview)
  * [Additional Protocols](introduction/additional_protocols.md)
  * [Additional Modules](introduction/additional_modules.md)
* [HTTPS Authentication](https_authentication/README.md)
  * [TLS Authentication Modes](https_authentication/tls_authentication_modes.md)
  * [Self-Generated Certificate](https_authentication/self-generated_certificate.md)
* [Start Guide](start_guide/README.md)
  * [Configure Server and Build Client](start_guide/configure_server_and_build_client.md)
   * [Solution for IPv4](start_guide/configure_server_and_build_client.md#solution-for-ipv4)
   * [Solution for IPv6](start_guide/configure_server_and_build_client.md#solution-for-ipv6)
  * [Run HTTPS Boot](start_guide/run_https_boot.md)

---

* Tables
  * [Table 1 - Certificate Requirement](https_authentication/tls_authentication_modes.md#table-1---certificate-requirement)
  * [Table 2 - Key Pair](https_authentication/self-generated_certificate.md#table-2---key-pair)

---

* Figures
 * [Figure 1 - Authentication Mechanism](https_authentication/README.md#figure-1-authentication-mechanism)
 * [Figure 2 - HTTPS Boot, IPv4 Configuration](start_guide/configure_server_and_build_client.md#figure-2-https-boot,-ipv4-configuration)
 * [Figure 3 - DHCPv4 Server Scope](start_guide/configure_server_and_build_client.md#figure-3---dhcpv4-server-scope)
 * [Figure 4 - DHCPv4 Server Options](start_guide/configure_server_and_build_client.md#figure-4---dhcpv4-server-options)
 * [Figure 5 - Configure New Host for IPv4](start_guide/configure_server_and_build_client.md#figure-5---configure-new-host-for-ipv4)
 * [Figure 6 - Add MIME Type](start_guide/configure_server_and_build_client.md#figure-6---add-mime-type)
 * [Figure 7 - Add MIME Type](start_guide/configure_server_and_build_client.md#figure-7---add-a-new-mime-type-to-iis)
 * [Figure 8 - Add Server Certificates](start_guide/configure_server_and_build_client.md#figure-8---add-server-certificates)
 * [Figure 9 - Enroll a Certificate for the HTTPS Server](start_guide/configure_server_and_build_client.md#figure-9---enroll-a-certificate-for-the-https-server)
 * [Figure 10 - Create a New Website for the HTTPS Server](start_guide/configure_server_and_build_client.md#figure-10---create-a-new-website-for-the-https-server)
 * [Figure 11 - The UEFI Shell file, as viewed in IIS](start_guide/configure_server_and_build_client.md#figure-11---the-uefi-shell-file-as-viewed-in-iis)
 * [Figure 12 - HTTPS boot, IPv6 Configuration](start_guide/configure_server_and_build_client.md#figure-12---https-boot-ipv6-configuration)
 * [Figure 13 - Configure Forward Lookup Zone for IPv6](start_guide/configure_server_and_build_client.md#figure-13---configure-forward-lookup-zone-for-ipv6)
 * [Figure 14 - Configure New Host for IPv6](start_guide/configure_server_and_build_client.md#figure-14---configure-new-host-for-ipv6)
 * [Figure 15 - UEFI Client Certificate Configuration](start_guide/run_https_boot.md#figure-15---uefi-client-certificate-configuration)
 * [Figure 16 - Select Boot Option](start_guide/run_https_boot.md#figure-16---select-boot-option)
 * [Figure 17 - Boot the Downloaded UEFI Shell Image](start_guide/run_https_boot.md#figure-17---boot-the-downloaded-uefi-shell-image)