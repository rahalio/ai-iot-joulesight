# JouleSight — User stories

**Product:** [PRODUCT.md](./PRODUCT.md)


### Embedded ML engineer

- As an ML engineer, I want energy predictions for candidate algorithms at two resolutions, so I pick the cheapest that clears accuracy.
- As an ML engineer, I want cloud-offload joule estimates, so I stop assuming “cloud is cheaper.”

### Power engineer

- As a power engineer, I want profile campaigns tied to meter IDs, so lab numbers are reproducible in the field.
- As a power engineer, I want duty-cycle modeling, so sleep current is not ignored.

### Fleet operator

- As a fleet operator, I want approved configs per site, so techs cannot flash an unbudgeted model.
- As a fleet operator, I want harvest-budget breaches flagged before deploy, so cameras do not die mid-event.

### Sustainability officer

- As a sustainability officer, I want fleet joules/inference trends, so edge choices show carbon impact vs cloud.

### Exception path

- As an ML engineer, I want the system to refuse a low-energy config below my accuracy floor, so safety is not bargained away.

### Admin

- As an admin, I want API keys scoped to device classes, so partners cannot see other fleets’ profiles.
