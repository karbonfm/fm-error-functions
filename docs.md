## Custom.Error ( descriptor;data)```/*
This is an example of a custom error created for some other module
notice we use -2 for the errorCode.

*/```## Error ( errorCode;descriptor;data)```/**
 *
 * wraps the error in a JSON Object
 *
 * @param {number} errorCode the FileMaker Error Code.
 * @param {string} descriptor describe where the error is happening
 * @param {object} [data] optional extra data you want to record
 * 
 * @return {object} an error object
 *
 * @module fm-error-functions
 * @see https://github.com/karbonfm/fm-error-functions
 *
 * @history 2017-10-01, todd@geistinteractive.com, created
 *
 */```## Error.Description ( errorCode)```/**
 *
 * looks up the error description
 *
 * @param {number} errorCode the FileMaker Error Code
 * 
 * @return {string} an error object
 *
 * @module fm-error-functions
 * @see https://github.com/karbonfm/fm-error-functions
 *
 * @history 2015-10-01, todd@geistinteractive.com, created
 *
 */```## Error.IsError ( thisError)```/**
 * tests the object for an errorCode.
 * if the errorCode is NOT "" or 0 it returns true
 *
 * @param {object} theError
 *
 * @return {boolean}
 *
 * @module fm-error-functions
 * @see https://github.com/karbonfm/fm-error-functions
 *
 * @history 2015-10-01, todd@geistinteractive.com, created
 *
 */```## Error.Last ( descriptor;data)```/**
 * wraps the Last FileMaker error in a JSON Object
 *
 * @param {string} descriptor describe where the error is happening
 * @param {object} [data] optional extra data you want to record
 *
 * @returns {object} error object
 *
 * @module fm-error-functions
 * @see https://github.com/karbonfm/fm-error-functions
 *
 * @history 2015-10-01, todd@geistinteractive.com, created
 *
 */```