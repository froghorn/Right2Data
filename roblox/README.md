# roblox
Roblox allows users to request Right to Access Reports. \
https://en.help.roblox.com/hc/en-us/articles/40630460625556-Right-to-Access-Reports \
\
When Roblox does not store certain information on your account, the relevant file will be populated as such: \
"Our search for your data returned no results in relation to this category" \
\
This .md is a WIP and may not contain all relevant information. Some values have been altered to retain privacy.
## data-file-1-account-closure-history.txt
\-unknown
## data-file-2-age-verification-history.txt
\-unknown
## data-file-3-billing-history.csv
contains a list of billing transactions associated with the given account
| Key | Example Values | Comments |
| - | - | - |
| `user_id` | `123` | |
| `provider_payment_id` | `ct-00000000-0000-4000-0000-000000000000` </br> `stripe-pi_0123456789aBcDeFgHiJkLmN` </br> `legacy_1234567890` | |
| `type` | `Charge` | |
| `timestamp_utc` | `2026-01-01 00:01:01` | |
| `status` | `Succeeded` | |
| `product_name` | `1 Robux` </br> `80 Robux` </br> `500 Robux` </br> `Turbo Builders Club Monthly` </br> `Roblox Premium 1000` </br> `Roblox Credit Redemption` | |
| `payment_method` | `CreditBalance` </br> `Stripe` | |
| `currency_code` | `USD` | |
| `amount` | `0.02` | |
| `is_recurring` | `False` </br> `True` | |
| `recurring_schedule_id` | `\x1234567890abcdefghijklmnopqrstuv` | |
| `first_name` | | |
| `last_name` | | |
| `full_name` | `John Doe` | |
| `email` | `account@example.com` | |
| `postal_code` | `55555` | |
| `country` | `US` | |
| `state` | `CA` | |
| `city` | `New York City` | |
| `credit_card_first_digits` | | |
| `credit_card_last_digits` | `0000` | |
## data-file-4-commerce-orders.txt
\-unknown
## data-file-5-console-identities.txt
\-unknown
## data-file-6-developer-subscription-history.txt
\-unknown
## data-file-7-devex-history.txt
\-unknown
## data-file-8-device-history.csv
contains a list of devices used to access the account
| Key | Example Values | Comments |
| - | - | - |
| `user_id` | `123` | |
| `platform_type` | `Android: unknown` </br> `Android: unknown phone` </br> `Desktop Mac Universal App` </br> `Desktop Windows Universal App` </br> `iOS: unknown phone` </br> `iOS: unknown tablet` </br> `iPad Pro 9.7` </br> `iPhone 14` </br> `iPone 5s` </br> `iphone 6s` </br> `Mac` </br> `Overall` </br> `PC` </br> `Roblox Studio for Mac` </br> `Roblox Studio for Windows` </br> `Unknown` </br> `UWP Universal App` </br> | |
| `first_observed` | `2026-01-01` | |
| `last_observed` | `2026-01-01` | |
## data-file-9-email-addresses.csv
contains a list of email addresses associated with the account
| Key | Example Values | Comments |
| - | - | - |
| `user_id` | `123` | |
| `email_address` | `account@example.com` | |
| `is_verified` | `True` | |
| `is_disabled` | `False` | |
| `email_added_utc` | `2026-01-01 00:01:01` | |
| `email_last_updated_utc` | `2026-01-01 00:01:01` | |
## data-file-10-government-ids.txt
\-unknown
## data-file-11-ip-addresses.csv
contains a list of known ip addresses associated with account
| Key | Example Values | Comments |
| - | - | - |
| `user_id` | `123` | |
| `ip_address` | `1.1.1.1` </br> `::ffff:10.2.27.7` | fun fact: `::ffff:10.2.27.7` is a real bogon ipv6 ip that was included in my report for some reason. |
| `first_recorded_utc` | `2026-01-01 00:01:01` | |
| `last_recorded_utc` | `2026-01-01 00:01:01` | |
| `last_observed_port` | `55555` | |
| `last_observed_port_utc` | `2026-01-01 00:01:01` | |
## data-file-12-locale-history.csv
contains a list of known locales associated with account
| Key | Example Values | Comments |
| - | - | - |
| `user_id` | `123` | |
| `observed_locale` | `en_us` | |
| `supported_locale` | `zh_cn` | |
| `created_utc` | `2026-01-01 00:01:01` | |
| `is_current` | `True` | |
## data-file-13-location-history.csv
contains a list of known locations associated with account
| Key | Example Values | Comments |
| - | - | - |
| `user_id` | `123` | |
| `country` | `United States` </br> `North Korea` </br> `China` </br> `China - Global App` | |
| `region` | `US-CA` | |
| `verified` | `False` </br> `True` | |
| `created_utc` | `2026-01-01 00:01:01` | |
| `is_current` | `False` </br> `True` | |
## data-file-14-login-history.csv
contains a list of known login times
| Key | Example Values | Comments |
| - | - | - |
| `user_id` | `123` | |
| `created_utc` | `2026-01-01 00:01:01` | |
## data-file-15-mac-addresses.csv
contains a list of known mac address associations
| Key | Example Values | Comments |
| - | - | - |
| `user_id` | `123` | |
| `mac_address` | `aa11bb22cc33` | |
| `first_observed_utc` | `2026-01-01 00:01:01` | |
## data-file-16-moderation-history.csv
contains a list of known moderation actions taken against the given account. Includes experience moderation events.
| Key | Example Values | Comments |
| - | - | - |
| `user_id` | `123` | |
| `created_utc` | `2026-01-01 00:01:01` | |
| `acknowledged_utc` | `2026-01-01 00:01:01` | |
| `Type` | `Delete` </br> `Experience Ban` | |
| `start_utc` | `2026-01-01 00:01:01` | |
| `end_utc` | `2026-01-01 00:01:01` | |
| `note` | `This username is not permitted on Roblox.` </br> `This field is freeform when coming from experience moderation`| |
| `universe_id` | `13058.0` | float |
| `universe_name` | `Crossroads`| |
| `action_type` | | |
| `invalidated_utc` | `2026-01-01 00:01:01` | |
## data-file-17-phone-numbers.csv
contains a list of known phone numbers associated with the account
| Key | Example Values | Comments |
| - | - | - |
| `user_id` | `123` | |
| `phone_number` | `15555555555` | |
| `created_utc ` | `2026-01-01 00:01:01` | |
| `is_verified` | `True` </br> `False` | |
| `is_active` | `False` </br> `True` | |
## data-file-18-previous-display-names.csv
contains a list of known prior display names associated with the account
| Key | Example Values | Comments |
| - | - | - |
| `user_id` | `123` | |
| `display_name` | `John Doe` | |
| `first_used_utc` | `2026-01-01 00:01:01` | |
## data-file-19-previous-usernames.txt
\-unknown
## data-file-20-promotion-channels.txt
\-unknown
## data-file-21-user-group-payouts.csv
contains a list of known user groups payouts associated with the account
| Key | Example Values | Comments |
| - | - | - |
| `user_id` | `123` | |
| `payout_id` | `1234567890` | |
| `group_id` | `2` | |
| `group_name` | `LOL` | |
| `currency` | `Robux` | |
| `amount` | `1` | |
| `grouppayouttypeid` | `1.0` | float |
| `grouppayoutsourceid` | | |
| `created_utc` | `2026-01-01 00:01:01` | |
## data-file-22-user-robux-earnings.csv
contains a list of known user earnings associated with the account
| Key | Example Values | Comments |
| - | - | - |
| `user_id` | `123` | |
| `seller_earnings` | `1` | |
| `affiliate_earnings` | `0` | |
| `creator_earnings` | `0` | |
| `group_payout_earnings` | `0` | |
| `premium_payout_earnings` | `0` | |
| `ads_earnings` | `0` | |
| `overall_earnings` | `1` | |
| `entity_type` | `User` | |
| `date`| `2026-01-01` | |
## data-file-23-user.csv
contains account information associated with the account
| Key | Example Values | Comments |
| - | - | - |
| `user_id` | `123` | |
| `user_name` | `JohnDoe` | |
| `display_name` | `John Doe` | |
| `description` | `"He came like the wind, like the wind touched everything, and like the wind was gone."` | |
| `date_of_birth` | `2000-01-01` | |
| `created_utc` | `2026-01-01 00:01:01` | |
| `gender` | `Male` | |
## data-file-24-virtual-economy-transactions.csv
contains virtual economy transactions associated with the account
| Key | Example Values | Comments |
| - | - | - |
| `user_id` | `123` | |
| `payment_unitprice` | `15` | |
| `paymentdate_utc` | `2026-01-01 00:01:01` | |
| `payment_created_utc` | `2026-01-01 00:01:01` | |
| `payment_updated_utc` | `2026-01-01 00:01:01` | |
| `product_id` | `1305046` | |
| `quantity` | `1` | |
| `sale_unitprice` | `0.0` | float |
| `discount` | `0` | |
| `total_price`| `15` | |
| `marketplace_fee` | `24` | |
| `sale_created_utc` | `2026-01-01 00:01:01` | |
| `sale_updated_utc` | `2026-01-01 00:01:01` | |
| `product_type` | `User Product` </br> `ROBLOX Product` </br> `Developer Product` </br> `Private Server Product` </br> `Collectible Item` </br> `Game Pass` | |
| `is_for_sale` | `True` </br> `False` | |
| `product_asset_id` | `1818.0` | float |
| `item_name` | `Upload Fee: Avatar Background` | |
| `asset_type` | `Animation` </br> `Audio` </br> `Avatar Background` </br> `Badge` </br> `Decal` </br> `Dress Skirt Accessory` </br> `Font Face` </br> `Gear` </br> `Hair Accessory` </br> `Hat` </br> `Image` </br> `Jacket Accessory` </br> `Lua` </br> `Mesh` </br> `MeshPart` </br> `Model` </br> `Pants` </br> `Pants Accessory` </br> `Place` </br> `Plugin` </br> `Shirt Accessory` </br> `Shorts Accessory` </br> `Shoulder Accessory` </br> `SolidModel` </br> `Sweater Accessory` </br> `T-Shirt` </br> `T-Shirt Accessory` </br> | |
| `product_created_utc` | `2026-01-01 00:01:01` | |
| `product_updated_utc` | `2026-01-01 00:01:01` | |
| `is_public_domain` | `False` </br> `True` | |
| `creator_type` | `Group (agentid)` </br> `User (userid)` | |
| `is_limited_edition` | `False` </br> `True` | |
| `is_resellable` | `False` </br> `True` | |
| `total_available` | | |
| `min_membership_type` | `0.0` | |
| `sale_platform_type_id` | `4` </br> `8` </br> `86` | |
| `sale_location_type_id` | `1` </br> `2` | |
| `sale_location_type` | `Website` </br> `Game` | |
| `sale_location_id` | `11433200331.0` | placeid, float |
| `source_id` | | |
| `product_type_high_level` | `Avatar Item` </br> `Developer Item` </br> `Game Item` </br> `Roblox Item` | |
| `product_universe_id` | `4065848437.0` | float |
| `product_target_id` | `1818.0` | float |
| `asset_id` | `1818.0` | float |
| `purchase_status` | `Success` </br> `Failure` | |
| `purchase_id` | `\x0123456789abcdefabcdefabcdefabcd` | |
| `purchase_id_payment_id` | `x0123456789abcdefabcdefabcdefabcd` | |
| `avatar_item_target_type` | `Asset` </br> `IEC Bundle` | |
| `avatar_item_limited_status` | `NonLimited` | |
| `avatar_item_resale_or_first_sale` | `First` | |
