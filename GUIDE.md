# Salesforce Release Confidence: decision guide

Connect technical test evidence to the CRM outcome.

**For:** CRM product owners, release managers and QA leads discussing Salesforce changes.

**Decision in focus:** Which CRM outcome still needs evidence beyond code-level checks?

## Separate technical thresholds from business acceptance

Salesforce describes Apex unit testing for classes and triggers and associated deployment requirements. Meeting a code-level requirement does not by itself explain whether a sales, service or other CRM journey produces the expected business outcome.

**Question to discuss:** Which CRM outcome is not answered by the existing code-level evidence?

## Include declarative and coded change

A release conversation may involve Flow, Apex, Lightning components or configuration. Name only the categories relevant to the change. The purpose is to discover where evidence is needed; this guide supplies no implementation-specific test design.

**Question to discuss:** Which change category and role are involved in the business outcome?

## Discuss permissions and cross-system behaviour

A journey can depend on user access, data visibility and a downstream or upstream service. Ask who owns those acceptance questions. Do not upload org metadata, customer records, connected-app details or tokens to a public conversation.

**Question to discuss:** Does acceptance change between broad user-role categories?

## Explain evidence in language the release owner can use

Component tests, code tests and business acceptance have different scopes. The linked vendor materials are starting points; verify their current applicability. A discovery conversation should establish the remaining question, its owner and the decision it affects.

**Question to discuss:** What uncertainty must the release owner explicitly accept or resolve?

## Read next

Read [source status and retrieval limitations](SOURCES.md), try the local mini tool using the [README instructions](README.md#start-here), or [discuss the question on LinkedIn](https://www.linkedin.com/in/manoj-rollo/). A short, non-confidential outline is enough. Professional assessment or delivery is separately scoped. This guide does not assess a system or approve a release.
