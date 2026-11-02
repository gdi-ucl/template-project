# Convert an existing project to the suggested GDI format

The minimum is one useful README. Keep working code and folders in their current layout; you do not have to rename everything or write YAML.

## Project currently on your computer

1. Identify the project lead, rights owner, intended audience and any publication restrictions.
2. Separate files allowed for GitHub from datasets, participant information, credentials and other externally stored assets. Inspect file contents and notebook outputs as well as names.
3. Create a repository using this blueprint (START-HERE.md).
4. Upload the permitted files, retaining an existing structure or using files.
5. Fill in README.md. Additional metadata files are optional.
6. Open the uploaded files and test external storage links as an intended collaborator.
7. Share the project URL. Add the intended collaborators if the project is private.

A browser upload records a snapshot and later GitHub changes; it does not import previous version history from a local Git repository. Ask the maintainer for help importing Git history if that matters.

## Project already in GitHub

1. Ensure you have repository Admin access and permission from the actual rights owner to move the work into gdi-ucl.
2. Check the full history for material that should not move or become public. Confirm destination-name availability and collaborator/team access implications.
3. Use the source repository's **Settings → General → Danger Zone → Transfer ownership**, enter gdi-ucl and follow GitHub's confirmations. Ask the organisation maintainer if the destination does not allow the transfer.
4. Verify the destination URL, visibility, collaborators, branches, releases and any integrations after transfer. Update links used by colleagues.
5. Add or adapt the blueprint README headings. Keep existing useful instructions. Do not overwrite an existing licence or author credits.

A repository transfer preserves its Git history. It may affect permissions or integrations, so verify them. This blueprint does not perform automatic transfers.

## Already published in another system

Keep the authoritative publication or data record there. Add an appropriate citation/link to README.md and upload only files permitted for this GitHub workspace.

Official transfer guide: https://docs.github.com/en/repositories/creating-and-managing-repositories/transferring-a-repository
