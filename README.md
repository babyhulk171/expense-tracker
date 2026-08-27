### Description
ExpenseTrack is a simple CLI app to track every money transaction, give summaries and store a history of the transactions.

### Scope
The app will accept transactions(expense and income), list transactions, give a summary of the transactions, show balance and filter by transaction's category.

### Examples
```expensetracker add expense coxinha 10.5 food```

```→ Transaction added.```

```expensetracker delete [transaction id]```

```→ Transaction deleted.```

```expensetracker list```

```→ coxinha -10.5 food
→ bonus +1000.5 work```

```expensetracker update [id] expense salgado 12.0 food```

```→ Transaction updated.```

```expensetracker summary```

```→ balance: R$990.0
→ incomes: R$1000.5
→ expenses: 10.5```

```expensetracker reset```

```→ You sure you want do reset? All transactions will be deleted. [y/N] y
→ All transactions deleted.```