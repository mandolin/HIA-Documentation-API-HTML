# Publication automation

## Repository context

This repository publishes a pinned HIA Documentation System HTML tool reference artifact. Read the root README, `snapshot.json` and `.github/workflows/pages.yml` before updating a snapshot. Current source ownership and publication identity are recorded in the snapshot.

## Update task

Build and validate the source repository, publish the fixed archive and report, update snapshot metadata, run the Pages workflow and verify the deployed locale roots. The source repository owns generation and archive validation.

## Validation checklist

Check the source commit and registry digest, archive and TAR digests, file/byte budgets, native fields, scoped bindings, source maps and complete-source digests. Verify both locale pages and links after deployment.

## Maintenance plan

Keep snapshot metadata synchronized with its immutable release. Recheck site and single-file budgets when adding content or retained documentation versions.

中文说明见根README。内容生成、回归及归档验证由固定源提交提供，发布仓维护公开说明、固定工件元数据与Pages工作流。
