# Functional Requirements

### Users
1. Users should be able to create an account
2. Users should be able to login
3. Users should be able to use SSO
4. Users should be able to reset password
5. Users should be able to use a guest mode. However, mods will not be saved and public for them.


### Mods
1. Users should be able create custom cards and turn into a mod
2. Users should be able to create custom relics and turn into a mod
3. Users should be able to create custom enemies and turn into a mod
4. Users should be able to create custom mods which are a composite of any card, relic, enemy mods
5. Mods should be versioned, and users can download any version of a mod

### Web app
1. Users should be able search for mod packs
2. Users should be able to upvote or downvote mod packs (downvotes invisible)


### Nonfunctional reqs

1. handle version updates gracefully
2. Limit entities per account (So there is no unbounded costs in case bot gets in)
3. Bot detection on account signup
