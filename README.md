# Task-Fragmentation
AN assignment to test the fragmentation ability of Developers

My Pick - Fragment the UI into selective components to make it more readable

## My Reasons for Fragmentating it like that

Componentization: I'll break down the large BurnPage component into smaller components, focusing on specific parts of the UI. For example, I'll create separate components for the burn button bar, burn stats container, transaction table, and chain selector.

Component Responsibilities: Each new component will have a clear and specific responsibility, making it easier to understand and maintain. For instance, the burn button bar component will handle the UI elements related to burning tokens, while the burn stats container component will display statistics related to token supply.

Reuse of Hooks: I'll ensure that custom hooks such as useWallet, useChainSelector, and useAppSupplies are still utilized within the appropriate components to maintain functionality and reusability.

Improving Readability: By breaking the UI into smaller components, the code will become more readable, as each component will focus on a specific aspect of the UI. This will also make it easier to navigate and understand the codebase for future developers.
