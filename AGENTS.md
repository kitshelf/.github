# AGENTS.md, kitshelf org

Instructions for any agent working on the kitshelf organization.

## What this repo is

This is the org profile repo for [github.com/kitshelf](https://github.com/kitshelf). GitHub renders
`profile/README.md` as the organization's public landing page.

## What the public "project list" actually is

The table in `profile/README.md` is the project list. It lists **20 planned kits** in build order. It is
not the repository list.

GitHub's own **Repositories** section on the org page shows only repositories that exist on GitHub. Planned
kits have no repository until one is created. So the org page can correctly show 20 projects in the README
while the Repositories section shows 2 repos. That is not a bug; it is the difference between "planned kit"
and "existing repo."

## Canonical order

The order in `profile/README.md` mirrors the vault's build order at
`my-2nd-brain/vault/projects/popular/_BUILD-ORDER.md`. When the order changes, update both. The README is
the public copy; the vault note is the reasoning.

## Updating the page

1. Edit `profile/README.md`.
2. Commit.
3. **Push to `main`.**

A local commit alone does not change the live page. The page updates only after the push. This is the
mistake that made the org page keep showing 15 projects while the local file showed 20.

## When adding a kit

- Create the kit repo under `kitshelf/`.
- Add its row to `profile/README.md` in build order.
- Keep the **Status** section accurate: `released`, `in development`, or `planned`.
- Do not list a kit as `released` until its repo and release exist.

## The 20 kits, in build order

1. ScamCheck — released
2. MechanicLens — in development
3. TomorrowBinder
4. ContractorLens
5. DebtLens
6. LeaseLens
7. DepositBack
8. MemoryBook
9. MedicareCallGuard
10. BillFight
11. ClosingDecode
12. VisitPrep
13. DenialAppeal
14. GrantTruth
15. IEPAlly
16. BenefitsLens
17. LabsPlain
18. SubSweep
19. Tribute
20. FuneralLens

## Rule

The README is the single public source of truth for the project list. Do not create a second copy that can
drift. If you need the list elsewhere, link to the README.
