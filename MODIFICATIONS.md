# RAGFlow Modifications

This directory contains a modified version of RAGFlow with the following changes:

## Changes Made

### conf/mapping.json
- Changed `"number_of_shards": 2` to `"number_of_shards": 1`
- Reason: Single-node Elasticsearch compatibility
- Commit: 25fac37f4

## Upstream Information

- Original repository: https://github.com/infiniflow/ragflow
- Based on commit: 81fede004 (Fix: refactor prompts)
- Last sync: September 9, 2025

## Updating

To update to newer upstream versions:
1. Check for updates in the original repository
2. Apply our modifications to the new version
3. Test the setup thoroughly
4. Update this documentation
