# TermLoanContract

## Abstract
This proposal is an implementation of Term Loan on a Blockchain.

### Motivation
Our financial institutions are not transparent enough when it comes to credit financing. We believe there are genuine use case for fair credit financing of individual needs and small businesses.

### Use Cases / Scenarios
- An existing MFB wants to increase demand of its loans
- Push potential customer credit profile to financial institutions
- If the loan provider request for a ask price(margin call), A borrower must supply 15% of the ask price.
- The margin call (a portion of the loan value) shall be kept in a fund should in case the borrower defaults.

### Specification
```
package smartcontracts;

/**
 * Available only to institutional investors. Banks.
 */
public class TermLoan {

	/**
	 * Validate successfully peering
	 */
	public void verify() {
		// TODO - implement TermLoan.verify
		throw new UnsupportedOperationException();
	}

	public void computeInterestRate() {
		// TODO - implement TermLoan.computeInterestRate
		throw new UnsupportedOperationException();
	}

	public void setRepaymentDuration() {
		// TODO - implement TermLoan.setRepaymentDuration
		throw new UnsupportedOperationException();
	}

	public void processRepayment() {
		// TODO - implement TermLoan.processRepayment
		throw new UnsupportedOperationException();
	}

	public void checkPaymentDate() {
		// TODO - implement TermLoan.checkPaymentDate
		throw new UnsupportedOperationException();
	}

	public void isValid() {
		// TODO - implement TermLoan.isValid
		throw new UnsupportedOperationException();
	}

	public void computeRepayments() {
		// TODO - implement TermLoan.computeRepayments
		throw new UnsupportedOperationException();
	}
}
```
