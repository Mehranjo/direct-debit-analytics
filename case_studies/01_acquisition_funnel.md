# Acquisition Funnel Analysis

## Business Problem

How efficiently do users move from OAuth initiation
to their first successful debit?

## Dataset

VW_REQUEST_AUDIT
VW_MANDATE
VW_TRANSACTION

## Funnel

A1 OAuth Requested

A2 OAuth Generated

A3 OAuth Completed

A4 Token Received

A5 Merchant Activated

A6 First Successful Debit

## SQL

See:

sql/funnels/acquisition_funnel.sql

## Findings

Most drop-off occurs between:

OAuth Generated
→ OAuth Completed

## Recommendation

Improve OAuth completion UX.