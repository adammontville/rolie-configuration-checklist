# ROLIE configuration-checklist information-type

## Document Status

This document is not yet an individual draft, but we intend to submit this draft to the SACM working group.

## Contributing

Be aware that all contributions to the specification fall under the "NOTE WELL"
terms outlined below.

If you have **editorial** suggestions, you can fork and submit a pull request or create an issue in this repository.  If you have semantic suggestions (i.e. design suggestions), please use GitHub issues.

## Building the Draft

This draft is being edited in Markdown, but we've included all output steps of the build process.  To build from the Markdown file, you're going to need to install `kramdown-2629` (Ruby) and `xml2rfc` (Python).

Installing `kramdown-2629`:

```
gem install kramdown-rfc2629
```

Intalling `xml2rfc`:
```sh
$ pip install xml2rfc
```

The following command can be used to build the text file:

```
kramdown-rfc2629 draft-mandm-sacm-rolie-checklistdescriptor.mkd > draft-mandm-sacm-rolie-checklistdescriptor.xml && xml2rfc draft-mandm-sacm-rolie-checklistdescriptor.xml
```

## NOTE WELL

Any submission to the [IETF](https://www.ietf.org/) intended by the Contributor
for publication as all or part of an IETF Internet-Draft or RFC and any
statement made within the context of an IETF activity is considered an "IETF
Contribution". Such statements include oral statements in IETF sessions, as
well as written and electronic communications made at any time or place, which
are addressed to:

 * The IETF plenary session
 * The IESG, or any member thereof on behalf of the IESG
 * Any IETF mailing list, including the IETF list itself, any working group
   or design team list, or any other list functioning under IETF auspices
 * Any IETF working group or portion thereof
 * Any Birds of a Feather (BOF) session
 * The IAB or any member thereof on behalf of the IAB
 * The RFC Editor or the Internet-Drafts function
 * All IETF Contributions are subject to the rules of
   [RFC 5378](https://tools.ietf.org/html/rfc5378) and
   [RFC 3979](https://tools.ietf.org/html/rfc3979)
   (updated by [RFC 4879](https://tools.ietf.org/html/rfc4879)).

Statements made outside of an IETF session, mailing list or other function,
that are clearly not intended to be input to an IETF activity, group or
function, are not IETF Contributions in the context of this notice.

Please consult [RFC 5378](https://tools.ietf.org/html/rfc5378) and [RFC
3979](https://tools.ietf.org/html/rfc3979) for details.

A participant in any IETF activity is deemed to accept all IETF rules of
process, as documented in Best Current Practices RFCs and IESG Statements.

A participant in any IETF activity acknowledges that written, audio and video
records of meetings may be made and may be available to the public.
