+++
draft = false
title = "API Definition Example"
date = 2015-08-01T09:31:36Z
+++

```
{
    "id": "55780c119b23c3000100004f",
    "name": "HttpBin",
    "slug": "httpbin",
    "api_id": "2fdd8512a856434a61f080da67a88851",
    "org_id": "55780af69b23c30001000000",
    "use_keyless": true,
    "use_oauth2": false,
    "oauth_meta": {
        "allowed_access_types": [],
        "allowed_authorize_types": [],
        "auth_login_redirect": ""
    },
    "auth": {
        "use_param": false,
        "use_cookie": false,
        "auth_header_name": ""
    },
    "use_basic_auth": false,
    "enable_jwt": false,
    "jwt_signing_method": "",
    "notifications": {
        "shared_secret": "",
        "oauth_on_keychange_url": ""
    },
    "enable_signature_checking": false,
    "hmac_allowed_clock_skew": -1,
    "definition": {
        "location": "header",
        "key": "x-api-version"
    },
    "version_data": {
        "not_versioned": true,
        "versions": {
            "Default": {
                "name": "Default",
                "expires": "",
                "paths": {
                    "ignored": [],
                    "white_list": [],
                    "black_list": []
                },
                "use_extended_paths": true,
                "extended_paths": {
                    "ignored": [],
                    "white_list": [],
                    "black_list": [],
                    "cache": [],
                    "transform": [],
                    "transform_response": [],
                    "transform_headers": [],
                    "transform_response_headers": [],
                    "hard_timeouts": [],
                    "circuit_breakers": [],
                    "url_rewrites": [],
                    "virtual": [],
                    "size_limits": []
                },
                "global_headers": {},
                "global_headers_remove": [],
                "global_size_limit": 0
            }
        }
    },
    "uptime_tests": {
        "check_list": [],
        "config": {
            "expire_utime_after": 0,
            "service_discovery": {
                "use_discovery_service": false,
                "query_endpoint": "",
                "use_nested_query": false,
                "parent_data_path": "",
                "data_path": "",
                "port_data_path": "",
                "use_target_list": false,
                "cache_timeout": 0,
                "endpoint_returns_list": false
            },
            "recheck_wait": 0
        }
    },
    "proxy": {
        "listen_path": "/test/",
        "target_url": "http://httpbin.org/",
        "strip_listen_path": true,
        "enable_load_balancing": false,
        "target_list": [],
        "check_host_against_uptime_tests": false,
        "service_discovery": {
            "use_discovery_service": false,
            "query_endpoint": "",
            "use_nested_query": false,
            "parent_data_path": "",
            "data_path": "",
            "port_data_path": "",
            "use_target_list": false,
            "cache_timeout": 0,
            "endpoint_returns_list": false
        }
    },
    "custom_middleware": {
        "pre": [],
        "post": [],
        "response": []
    },
    "cache_options": {
        "cache_timeout": 60,
        "enable_cache": true,
        "cache_all_safe_requests": false,
        "enable_upstream_cache_control": false
    },
    "session_lifetime": 0,
    "active": true,
    "auth_provider": {
        "name": "",
        "storage_engine": "",
        "meta": {}
    },
    "session_provider": {
        "name": "",
        "storage_engine": "",
        "meta": null
    },
    "event_handlers": {
        "events": {}
    },
    "enable_batch_request_support": false,
    "enable_ip_whitelisting": false,
    "allowed_ips": [],
    "dont_set_quota_on_create": false,
    "expire_analytics_after": 0,
    "response_processors": [],
    "CORS": {
        "enable": false,
        "allowed_origins": [],
        "allowed_methods": [],
        "allowed_headers": [],
        "exposed_headers": [],
        "allow_credentials": false,
        "max_age": 0,
        "options_passthrough": false,
        "debug": false
    },
    "domain": "",
    "tags": []
}
```