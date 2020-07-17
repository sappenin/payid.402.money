This is the PayID "manual-mode" discovery endpoint for `alice`. However, Alice's PayID is serviced by "interactive mode" [PayID Discovery](https://github.com/payid-org/rfcs/blob/master/dist/spec/payid-discovery.txt#L293), which takes precedence.

You should re-attempt resolution using interactive-mode discovery, or else attempt to resolve the PayID `users/alice$payid.402.money`, which is equivalent to [the PayID you are looking for](https://payid.402.money/users/alice).
