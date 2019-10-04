## API Report File for "@azure/logger"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import debug from 'debug';

// Warning: (ae-forgotten-export) The symbol "AzureDebugger" needs to be exported by the entry point logger.d.ts
// 
// @public
export const AzureLogger: AzureDebugger;

// @public
export interface AzureLogger {
    // (undocumented)
    error: debug.Debugger;
    // (undocumented)
    info: debug.Debugger;
    // (undocumented)
    verbose: debug.Debugger;
    // (undocumented)
    warning: debug.Debugger;
}

// @public
export type AzureLogLevel = "verbose" | "info" | "warning" | "error";

// @public
export function createClientLogger(namespace: string): AzureLogger;

// @public
export function getLogLevel(): "verbose" | "info" | "warning" | "error" | undefined;

// @public
export function setLogLevel(level?: AzureLogLevel): void;


// (No @packageDocumentation comment for this package)

```