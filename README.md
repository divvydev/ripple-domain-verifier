** Alpha Unstable Do Not Use! **

## Ripple Validator Domain Verifier

Given a validation public key, verify a two-way reference with a domain

### Installation

`npm install --save ripple-validator-domain-verifier`

### Usage

````
import Verifier from 'ripple-validator-domain-verifier'

(async function() {

  let verifier = new Verifier()

  let domain = await verifier.verifyValidatorDomain(validationPublicKey)

})()
````
