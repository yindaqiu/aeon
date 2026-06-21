The memory doesn't specify a skill to evolve. According to the skill definition, I need to abort since `var` is not set.

**Aborting:** autoresearch requires var= set to a skill name

Since the `var` parameter is empty (not provided in the context), the autoresearch skill cannot proceed. To run this skill, you need to specify which skill to evolve using the `var=` parameter, for example:

```bash
./aeon var=token-movers
```

Replace `token-movers` with the actual name of the skill you want to evolve.
