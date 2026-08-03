# Roles & Permissions

Nations are run through **roles**. A role is a named rank (e.g. *Leader*, *Trusted*, *Member*) that
carries a set of **permissions**. Members hold a role; changing a role's permissions changes it for
**everyone** who holds that role.

Open **Nation Menu → Nation Management → Members & Permissions** (Java), or use commands:

| Command | What it does |
|---|---|
| `/nation roles` | List your nation's roles and how many members each has. |
| `/nation role create <name>` | Make a new role. |
| `/nation role delete <name>` | Delete a role - it must have no members first. |
| `/nation role set <player> <role>` | Assign a member to a role. |
| `/nation role title <role> <new title>` | Rename a role's display title (shown on nameplates). |
| `/nation perms ...` | Inspect and toggle a role's permissions (or use the GUI's green/red toggles). |

The **leader** always holds every permission and can't be reassigned or kicked. If you don't have
permission to manage members or roles yourself, the Members panel becomes a **read-only roster**.

## The permission list

| Permission | Grants |
|---|---|
| **Claim Land** | Claim chunks for the nation |
| **Unclaim Land** | Release nation chunks |
| **Place Blocks** | Place blocks in nation territory |
| **Break Blocks** | Break blocks in nation territory |
| **Open Containers** | Open chests and other containers in nation territory |
| **Invite Players** | Invite players to the nation |
| **Kick Players** | Remove members |
| **Manage Roles** | Create, edit, and delete roles, and assign them to members |
| **Manage Diplomacy** | Treaties, enemies, neutrality toggle, declaring/cancelling/surrendering wars, reinforcing allies, and letters |
| **Bank Deposit** | Deposit to the nation bank |
| **Bank Withdraw** | Withdraw from the bank, send foreign aid, and collect received aid |
| **Manage Taxes** | Set the daily member tax rate and manage exemptions - see [Tax & Upkeep](../economy/tax-upkeep.md) |
| **Edit Labels** | Colour, description, government, ideology, capital location, and banner |
| **Edit Banner** | Edit the nation banner |
| **Rename Nation** | Rename the nation and change its tag |
| **Send Announcements** | Broadcast nation announcements |
| **Manage Plots** | Assign or release [personal plots](claims-territory.md#personal-plots) on claimed chunks |
| **Disband Nation** | Disband the nation *(leader only)* |

## Default roles

Every nation starts with three roles. All three (including their permissions and display titles)
can be freely edited, renamed, or reassigned like any other role - these are just sensible starting
points, not fixed tiers.

- **Member** can **build, break, and open containers** inside claims, and **deposit** to the bank -
  but **cannot claim/unclaim land** by default. New invitees land here.
- **Trusted** adds **Claim/Unclaim Land**, **Invite/Kick Players**, **Manage Roles**, and **Send
  Announcements** on top of everything Member has.
- The **Leader** always has every permission, regardless of role edits, and can't be reassigned or
  kicked.

**Manage Plots** isn't included in Member or Trusted's starting permissions - only the Leader has it
by default. Grant it to Trusted (or a custom role) if you want to delegate assigning personal plots.

!!! info "Claiming is Trusted-level by default"
    A plain Member can't claim or unclaim land unless their role is specifically granted the
    **Claim Land** / **Unclaim Land** permissions. If you want all members to be able to claim,
    grant those two permissions to the Member role.
