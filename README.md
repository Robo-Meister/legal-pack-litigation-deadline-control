# Court & Litigation Deadline Pack

`legal-pack-litigation-deadline-control` is a starter Legal Office matter pack for court matter timelines, court communication history, document logs, deadline control, responsible owner assignment, filing/service review gates, followup, and matter closing. It depends on `legal-office-app` and adds litigation-specific workflow, document, checklist, risk-tag, and AI-boundary definitions.

## Included workflows

- `court_matter_intake`
- `court_document_registration`
- `deadline_creation`
- `responsible_owner_assignment`
- `court_communication_log`
- `filing_service_review`
- `deadline_followup`
- `matter_closing`

## Included document types

- `court_letter`
- `claim`
- `response`
- `court_order`
- `proof_of_service`
- `evidence_attachment`
- `deadline_note`
- `review_summary`

## Included checklists and rules

- `court_reference_required`
- `party_data_required`
- `deadline_required_for_court_document`
- `owner_required_for_deadline`
- `human_review_before_filing`
- `proof_of_service_required`
- `timeline_update_required`

## Dependencies

Required:

- `legal-office-app`
- `documents`
- `bpm`
- `calendar`
- `crm`

Optional:

- `communication`
- `ai-module`
- `risk`

## Deadline and review boundaries

This pack supports deadline control, court communication history, filing/service review gate tracking, and owner assignment. Deadline records and filing/service actions require human validation before use. Court-deadline determinations require human validation, and the pack does not autonomously file or serve documents.
