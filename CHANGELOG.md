# Changelog

## v2.0.1

### Bug Fixes

- Fixed WebSocket connection not validating room membership, allowing users to eavesdrop on other users' private conversations.
- Removed hardcoded demo user credentials that were active in production mode.
- Fixed admin role bypass vulnerability where regular users could access admin-only endpoints.
- Hardened JWT token validation to reject tokens with altered claims or missing signatures.
- Fixed email verification flow not properly requiring verification before account activation.