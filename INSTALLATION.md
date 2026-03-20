# Installing Architecture Starters

Projects are created from the AGENTIC-TEMPLATE repository.

After creating the project, architecture starters can be installed.

---

## Typical Installation Order

Optional pre-step for domain foundation starters:

0. Foundation (manual-adoption, if needed)

1. Backend
2. Frontend
3. Contracts
4. Infrastructure
5. Composition

---

## Example Project Structure

After installing all starters:

app/
  backend/  (agentic-clean-backend or agentic-dotnet-backend)
  web/      (agentic-react-spa or agentic-angular-spa)
  client/
  infra/
  contracts/
  composition/

docs/
.github/

---

Foundation starter note:

- Foundation starters (for example agentic-iam and agentic-auth-foundation) are adopted manually, not auto-installed into a runtime slot.
- Recommended adoption model: manual copy or subtree-vendor of docs and governance artifacts.
- Foundation starters define domain and policy baselines that downstream projects map into their own runtime implementation work.
