# Permissions Reference

Permissions live on **roles**, not individual members — see
[Roles & Permissions](../nations/roles-permissions.md) for how to grant them.

| Permission | Grants |
|---|---|
| **Claim Land** | Claim chunks for the nation |
| **Unclaim Land** | Release nation chunks |
| **Place Blocks** | Place blocks in nation territory |
| **Break Blocks** | Break blocks in nation territory |
| **Open Containers** | Open chests and other containers in nation territory |
| **Invite Players** | Invite players to the nation |
| **Kick Players** | Remove members |
| **Manage Roles** | Create, edit, and delete roles and assign them |
| **Manage Diplomacy** | Treaties, enemies, neutrality toggle, declaring/cancelling/surrendering wars, reinforcing allies, and letters |
| **Bank Deposit** | Deposit to the nation bank |
| **Bank Withdraw** | Withdraw from the bank, send aid, and collect received aid |
| **Manage Taxes** | *(Reserved — taxes are planned but not built yet)* |
| **Edit Labels** | Colour, description, government, ideology, capital location, and banner |
| **Edit Banner** | Edit the nation banner |
| **Rename Nation** | Rename the nation and change its tag |
| **Send Announcements** | Broadcast nation announcements |
| **Disband Nation** | Disband the nation *(leader only)* |

## Default roles

- **Member** *(default)* can **build, break, and open containers** inside claims, and **deposit**
  to the bank — but **cannot claim/unclaim land**.
- **Officer** *(default)* adds **Claim/Unclaim Land**, **Invite/Kick Players**, **Manage Roles**,
  and **Send Announcements**.
- The **Leader** always has every permission.

!!! info
    Claiming and unclaiming land is an **officer-level** ability by default — a plain Member can't
    claim unless their role is granted **Claim Land** / **Unclaim Land**.
