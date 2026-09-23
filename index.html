<html lang="id" class="scroll-smooth"><head><script data-bard-client-injected="true">(function(firebaseConfig, initialAuthToken, appId) {
        window.__firebase_config = firebaseConfig;
        window.__initial_auth_token = initialAuthToken;
        window.__app_id = appId;
            })("\n{\n  \"apiKey\": \"AIzaSyCqyCcs2R2e7AegGjvFAwG98wlamtbHvZY\",\n  \"authDomain\": \"bard-frontend.firebaseapp.com\",\n  \"projectId\": \"bard-frontend\",\n  \"storageBucket\": \"bard-frontend.firebasestorage.app\",\n  \"messagingSenderId\": \"175205271074\",\n  \"appId\": \"1:175205271074:web:2b7bd4d34d33bf38e6ec7b\"\n}\n","eyJhbGciOiJSUzI1NiIsImtpZCI6IjExNjRiNzdiNDMzZDdhMDAyMWI4NjE4YjhjYTU3ZTMyZGI5MWUxMTMiLCJ0eXAiOiJKV1QifQ.eyJzdWIiOiJmaXJlYmFzZS1hZG1pbnNkay1mYnN2Y0BiYXJkLWZyb250ZW5kLmlhbS5nc2VydmljZWFjY291bnQuY29tIiwiYXVkIjoiaHR0cHM6Ly9pZGVudGl0eXRvb2xraXQuZ29vZ2xlYXBpcy5jb20vZ29vZ2xlLmlkZW50aXR5LmlkZW50aXR5dG9vbGtpdC52MS5JZGVudGl0eVRvb2xraXQiLCJ1aWQiOiIwMTAxMDE3MTEwMDU0OTIwOTAwOCIsImlzcyI6ImZpcmViYXNlLWFkbWluc2RrLWZic3ZjQGJhcmQtZnJvbnRlbmQuaWFtLmdzZXJ2aWNlYWNjb3VudC5jb20iLCJjbGFpbXMiOnsiYXBwSWQiOiJjXzBhYThlNGNhYTc3Yzk4YmVfaW5kZXguaHRtbC0zOTcifSwiZXhwIjoxNzkwMTgzOTAxLCJpYXQiOjE3OTAxODAzMDEsImFsZyI6IlJTMjU2In0.Mgo8V-xNEg7vv72i_HVk0Ega1X3kmk0uwpeCh7L823H_GJcFlXQ5O-hcV9V88dvhSqyviGXP_1nRbD_8cfAyPV3BwT7TNTjiie6aYeKP_MmVdUmmDiDjm-pPqHOXSB1ZkGrRidc8LWsNHKa_rxYl0TyVgiTS679WNDCG9gbQ6PDX6oIPQ_k47iH9TKW-_0pN5l1LO0o4k2lgVlY3h-JNJxkk13fYVMDom6SetwXM3GRvL7Ep0Bykd862DRkDiHUVKK51r3TUt9XSaQgQp9Os9q0VY-8N0OaBo2XoM3HX5PfsgR2W1hfPHaVQxihOKvhcrz3l_PnaVq8OmabsOjv5CQ","c_0aa8e4caa77c98be_index.html-397")</script><script data-bard-client-injected="true">
  document.addEventListener('input', (event) => {
    if (event.target && (event.target.isContentEditable || event.target.hasAttribute('contenteditable'))) {
      const clonedDoc = document.cloneNode(true);
      const injectedScripts = clonedDoc.querySelectorAll('[data-bard-client-injected="true"]');
      injectedScripts.forEach(el => el.remove());
      window.parent.postMessage({
        type: 'inlineEdit',
        html: '<!DOCTYPE html>\n' + clonedDoc.documentElement.outerHTML
      }, '*');
    }
  });
</script><script data-bard-client-injected="true">(function(){'use strict';window.addEventListener("message",a=>{a.data&&a.data.type==="SUPPLEMENTAL_DATA_UPDATE"&&window.dispatchEvent(new CustomEvent("supplementaldataupdate",{detail:a.data.data}))});}).call(this);
</script><script data-bard-client-injected="true">(function() {
  const SCROLL_KEYS = new Set([
    'ArrowUp', 'ArrowDown', 'ArrowLeft', 'ArrowRight',
    ' ', 'Spacebar', 'PageUp', 'PageDown', 'Home', 'End',
  ]);
  const HORIZONTAL_KEYS = new Set(['ArrowLeft', 'ArrowRight']);

  function isTextEntryTarget(target) {
    if (!target) return false;
    const tagName = target.tagName;
    return tagName === 'INPUT' || tagName === 'TEXTAREA' ||
        tagName === 'SELECT' || target.isContentEditable === true;
  }

  // An element absorbs the key only if it both overflows on the axis being
  // scrolled and is configured to scroll on that axis. The cheap dimension
  // test runs first because getComputedStyle forces a style recalc, and this
  // runs on every keypress. Each axis is read from its own longhand: the
  // 'overflow' shorthand serializes as two values when the axes differ, which
  // is the common 'overflow-x: hidden; overflow-y: auto' pane.
  function canScroll(node, horizontal) {
    const overflows = horizontal ? node.scrollWidth > node.clientWidth
                                 : node.scrollHeight > node.clientHeight;
    if (!overflows) return false;
    const style = window.getComputedStyle(node);
    const overflow = horizontal ? style.overflowX : style.overflowY;
    return overflow === 'auto' || overflow === 'scroll';
  }

  // Walks up from the event target so nested scrollers keep their behavior.
  // <body> is included because pages that pin the root height make it the
  // scroll container.
  function hasScrollableAncestor(target, horizontal) {
    let node = target;
    while (node && node !== document.documentElement) {
      if (canScroll(node, horizontal)) return true;
      node = node.parentElement;
    }
    return false;
  }

  function rootCanScroll(horizontal) {
    const scroller = document.scrollingElement || document.documentElement;
    if (!scroller) return false;
    // Tolerate a pixel of rounding so subpixel layouts do not look scrollable.
    return horizontal ? scroller.scrollWidth > window.innerWidth + 1
                      : scroller.scrollHeight > window.innerHeight + 1;
  }

  window.addEventListener('keydown', function(event) {
    if (!SCROLL_KEYS.has(event.key)) return;
    if (event.defaultPrevented) return;
    // Alt and Meta turn arrows into browser history navigation, and Ctrl is
    // reserved for shortcuts, so none of them are scroll intent.
    if (event.altKey || event.metaKey || event.ctrlKey) return;

    const target = event.target;
    if (isTextEntryTarget(target)) return;

    // Anything that can still absorb the scroll gets to keep it.
    const horizontal = HORIZONTAL_KEYS.has(event.key);
    if (rootCanScroll(horizontal)) return;
    if (hasScrollableAncestor(target, horizontal)) return;

    event.preventDefault();
  }, {capture: true, passive: false});
})();</script><script data-bard-client-injected="true">(function() {
  // Ensure this script is executed only once
  if (window.firebaseAuthBridgeScriptLoaded) {
    return;
  }
  window.firebaseAuthBridgeScriptLoaded = true;

  let nextTokenPromiseId = 0;

  // Stores { resolve, reject } for ongoing token requests
  const pendingTokenPromises = {};

  // Listen for messages from the Host Application
  window.addEventListener('message', function(event) {

    const messageData = event.data;

  if (messageData && messageData.type === 'RESOLVE_NEW_FIREBASE_TOKEN') {
      const { success, token, error, promiseId } = messageData ?? {};
      if (pendingTokenPromises[promiseId]) {
        if (success) {
          pendingTokenPromises[promiseId].resolve(token);
        } else {
          pendingTokenPromises[promiseId].reject(new Error(error || 'Token refresh failed from host.'));
        }
        delete pendingTokenPromises[promiseId];
      }
    }
  });

  // Expose a function for the Generated App to request a new Firebase token
  window.requestNewFirebaseToken = function() {
    const currentPromiseId = nextTokenPromiseId++;
    const promise = new Promise((resolve, reject) => {
      pendingTokenPromises[currentPromiseId] = { resolve, reject };
    });
    if (window.parent && window.parent !== window) {
      window.parent.postMessage({
        type: 'REQUEST_NEW_FIREBASE_TOKEN',
        promiseId: currentPromiseId
      }, '*');
    } else {
      pendingTokenPromises[currentPromiseId].reject(new Error('No parent window to request token from.'));
      delete pendingTokenPromises[currentPromiseId];
    }
    return promise;
  };
})();</script><script data-bard-client-injected="true">
let realOriginalGetUserMedia = null;
if (navigator.mediaDevices && navigator.mediaDevices.getUserMedia) {
  realOriginalGetUserMedia = navigator.mediaDevices.getUserMedia.bind(navigator.mediaDevices);
}

(function() {
  if (navigator.mediaDevices && navigator.mediaDevices.__proto__) {
    try {
      Object.defineProperty(navigator.mediaDevices.__proto__, 'getUserMedia', {
        get: function() {
          return undefined; // Or throw an error
        },
        configurable: false
      });
    } catch (error) {
      console.error("Error defining prototype getter:", error);
    }
  }
})();

(function() {
  const pendingMediaResolvers = {};
  let nextMediaPromiseId = 0;

  function requestMediaPermissions(constraints) {
    const mediaPromiseId = nextMediaPromiseId++;
    const promise = new Promise((resolve, reject) => {
      pendingMediaResolvers[mediaPromiseId] = (granted) => {
        delete pendingMediaResolvers[mediaPromiseId];
        resolve(granted);
      };
    });

    window.parent.postMessage({
      type: 'requestMediaPermission',
      constraints: constraints,
      promiseId: mediaPromiseId,
    }, '*');

    return promise;
  }

  let originalGetUserMedia = realOriginalGetUserMedia;

  function interceptGetUserMedia() {
    if (navigator.mediaDevices) {
      Object.defineProperty(navigator.mediaDevices, 'getUserMedia', {
        value: function(constraints) {
          return requestMediaPermissions(constraints).then((granted) => {
            if (granted) {
              if (originalGetUserMedia) {
                return originalGetUserMedia(constraints);
              } else {
                throw new Error("Original getUserMedia not available.");
              }
            } else {
              throw new DOMException('Permission denied', 'NotAllowedError');
            }
          });
        },
        writable: false,
        configurable: false
      });
    }
  }

  interceptGetUserMedia();

  const observer = new MutationObserver(function(mutationsList, observer) {
    for (const mutation of mutationsList) {
      if (mutation.type === 'reconfigured' && mutation.name === 'getUserMedia' && mutation.object === navigator.mediaDevices) {
        interceptGetUserMedia();
      } else if (mutation.type === 'attributes' && mutation.attributeName === 'getUserMedia' && mutation.target === navigator.mediaDevices) {
        interceptGetUserMedia();
      } else if (mutation.type === 'childList' && mutation.addedNodes) {
        mutation.addedNodes.forEach(node => {
          if (node === navigator.mediaDevices) {
            interceptGetUserMedia();
          }
        });
      }
    }
  });

  function interceptSpeechRecognition() {
    if (!window.SpeechRecognition && !window.webkitSpeechRecognition) {
      return;
    }

    const OriginalSpeechRecognition = window.SpeechRecognition || window.webkitSpeechRecognition;

    const SpeechRecognitionWrapper = function(...args) {
      const recognizer = new OriginalSpeechRecognition(...args);
      const originalStart = recognizer.start.bind(recognizer);

      recognizer.start = function() {
        requestMediaPermissions({ audio: true }).then(granted => {
          if (granted) {
            originalStart();
          } else {
            const errorEvent = new SpeechRecognitionErrorEvent('error');
            errorEvent.error = 'not-allowed'; // This is the standard error for permission denial.
            recognizer.dispatchEvent(errorEvent);
          }
        });
      };

      return recognizer;
    };

    SpeechRecognitionWrapper.prototype = OriginalSpeechRecognition.prototype;
    SpeechRecognitionWrapper.prototype.constructor = SpeechRecognitionWrapper;

    if (window.SpeechRecognition) {
      window.SpeechRecognition = SpeechRecognitionWrapper;
    }
    if (window.webkitSpeechRecognition) {
      window.webkitSpeechRecognition = SpeechRecognitionWrapper;
    }
  }

  interceptSpeechRecognition();

  window.addEventListener('message', function(event) {
    if (event.data) {
      if (event.data.type === 'resolveMediaPermission') {
        const { promiseId, granted } = event.data;
        if (pendingMediaResolvers[promiseId]) {
          pendingMediaResolvers[promiseId](granted);
        }
      }
    }
  });

})();</script><script ws-interception-config="{&quot;parentOrigin&quot;:&quot;https://gemini.google.com&quot;,&quot;proxiedDomains&quot;:[]}" data-bard-client-injected="true">(function(){'use strict';var u=typeof Object.defineProperties=="function"?Object.defineProperty:function(b,d,e){if(b==Array.prototype||b==Object.prototype)return b;b[d]=e.value;return b};function v(b){b=["object"==typeof globalThis&&globalThis,b,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var d=0;d<b.length;++d){var e=b[d];if(e&&e.Math==Math)return e}throw Error("Cannot find global object");}var w=v(this);
function y(b,d){if(d)a:{var e=w;b=b.split(".");for(var h=0;h<b.length-1;h++){var k=b[h];if(!(k in e))break a;e=e[k]}b=b[b.length-1];h=e[b];d=d(h);d!=h&&d!=null&&u(e,b,{configurable:!0,writable:!0,value:d})}}function z(b){function d(h){return b.next(h)}function e(h){return b.throw(h)}return new Promise(function(h,k){function m(n){n.done?h(n.value):Promise.resolve(n.value).then(d,e).then(m,k)}m(b.next())})}y("globalThis",function(b){return b||w});/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
function A(b,d){function e(){}e.prototype=d.prototype;b.j=d.prototype;b.prototype=new e;b.prototype.constructor=b;b.h=function(h,k,m){for(var n=Array(arguments.length-2),p=2;p<arguments.length;p++)n[p-2]=arguments[p];return d.prototype[k].apply(h,n)}};function B(b,d,e="*"){function h(a){if(typeof a==="string")return F.encode(a).buffer;if(a instanceof ArrayBuffer)return a.slice(0);if(ArrayBuffer.isView(a))return a.buffer.slice(a.byteOffset,a.byteOffset+a.byteLength);throw Error("Invalid data type");}function k(a){a=h(a);var f={type:"send",data:new Uint8Array(a)},g;(g=r)==null||g.postMessage(f,[a])}function m(){if(!r)throw Error("Data port not captured yet.");r.onmessage=a=>{if(a.data.type==="message"){a=new MessageEvent("message",{data:G.decode(a.data.data)});
let f;(f=c.onmessage)==null||f.call(c,a);c.dispatchEvent(a)}}}function n(){if(!t)throw Error("Control port not captured yet.");t.onmessage=a=>{switch(a.data.type){case "open":l=1;var f=new Event("open"),g;(g=c.onopen)==null||g.call(c,f);c.dispatchEvent(f);q.forEach(H=>{k(H)});q=[];break;case "close":g=a.data;l=3;g=new CloseEvent("close",{code:g.code,reason:g.reason,wasClean:g.wasClean});(f=c.onclose)==null||f.call(c,g);c.dispatchEvent(g);break;case "error":l=3;f=new Event("error");let x;(x=c.onerror)==
null||x.call(c,f);c.dispatchEvent(f)}}}function p(a){return z(function*(){var f=new MessageChannel;t=f.port1;var g=new MessageChannel;r=g.port1;n();m();window.parent.postMessage({type:"websocket_open",portOrdering:["control","data"],url:b,protocols:a||[],connectionId:I},e,[f.port2,g.port2])}())}var c=Reflect.construct(EventTarget,[],new.target);c.CONNECTING=0;c.OPEN=1;c.CLOSING=2;c.CLOSED=3;c.url=b;c.binaryType="arraybuffer";c.protocol="";c.i="";var l=0,t=null,r=null,q=[],F=new TextEncoder,G=new TextDecoder;
c.onopen=null;c.onmessage=null;c.onclose=null;c.onerror=null;Object.defineProperty(c,"readyState",{get:()=>l,enumerable:!0,configurable:!0});Object.defineProperty(c,"bufferedAmount",{get:()=>{var a=0;q.forEach(f=>{a+=typeof f==="string"?f.length:f.byteLength});return a},enumerable:!0,configurable:!0});var I=function(){var a;return((a=globalThis.crypto)==null?0:a.randomUUID)?globalThis.crypto.randomUUID():"xxxxxxxx-xxxx-4xxx-yxxx-xxxxxxxxxxxx".replace(/[xy]/g,f=>{var g=Math.random()*16|0;return(f===
"x"?g:g&3|8).toString(16)})}();c.send=a=>{if(l===1)a instanceof Blob?a.arrayBuffer().then(f=>{k(f)}):k(a);else if(l===0)if(typeof a==="string")q.push(a);else if(a instanceof ArrayBuffer||ArrayBuffer.isView(a))q.push(h(a));else throw Error("Sending Blob is not supported before the connection is open.");else console.debug("WebSocket send called in CLOSING or CLOSED state; ignored.")};c.close=(a=1E3,f="")=>{if(l!==2&&l!==3){l=2;a={type:"close",code:a,reason:f,wasClean:a===1E3};var g;(g=t)==null||g.postMessage(a)}};
Promise.resolve().then(()=>p(d));return c}A(B,EventTarget);var C=document.currentScript,D=C==null?void 0:C.getAttribute("ws-interception-config");if(!D)throw Error("WebSocket Interceptor: Missing ws-interception-config attribute in the script tag.");var E=JSON.parse(D);if(!E.parentOrigin||typeof E.parentOrigin!=="string")throw Error("WebSocket Interceptor: Invalid parentOrigin in ws-interception-config");
(function(b){var d=Object.getOwnPropertyDescriptor(window,"WebSocket");if(!d||d.writable||d.configurable)d=Object.assign(function(e,h){try{let k=(new URL(e)).hostname;if(b.proxiedDomains.some(m=>k===m||k.endsWith(`.${m}`)))return new B(e,h,b.parentOrigin)}catch(k){throw window.parent.postMessage({type:"websocket_blocked",url:e,reason:"blocked_invalid_url"},b.parentOrigin),new DOMException(`WebSocket connection to '${e}' is not allowed in Canvas.`,"SecurityError");}window.parent.postMessage({type:"websocket_blocked",
url:e,reason:"blocked_domain_not_allowlisted"},b.parentOrigin);throw new DOMException(`WebSocket connection to '${e}' is not allowed in Canvas.`,"SecurityError");},{CONNECTING:0,OPEN:1,CLOSING:2,CLOSED:3}),Object.defineProperty(window,"WebSocket",{value:d,writable:!1,configurable:!1})})({proxiedDomains:E.proxiedDomains||[],parentOrigin:E.parentOrigin});}).call(this);
</script><script data-bard-client-injected="true">((function(modelInformation) {
  const originalFetch = window.fetch;
  // TODO: b/421908508 - Move these out of the script and match all generative AI model calls.
  let googleLlmBaseApiUrls = [
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.textModelName + ':streamGenerateContent',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.textModelName + ':generateContent',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.imageModelName + ':predict',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.imageModelName + ':predictLongRunning',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.imageEditModelName + ':generateContent',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.imageTransformModelName + ':generateContent',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.videoModelName + ':predict',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.videoModelName + ':predictLongRunning',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.ttsModelName + ':generateContent',
  ];
  modelInformation.deprecatedTextModelNames.forEach((modelName) => {
    googleLlmBaseApiUrls.push(
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':streamGenerateContent',
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':generateContent',
    );
  });
  modelInformation.deprecatedImageModelNames.forEach((modelName) => {
    googleLlmBaseApiUrls.push(
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':predict',
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':predictLongRunning',
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':generateContent',
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':streamGenerateContent',
    );
  });
  modelInformation.deprecatedGenerateImageModelNames.forEach((modelName) => {
    googleLlmBaseApiUrls.push(
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':generateContent',
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':streamGenerateContent',
    );
  });
  modelInformation.deprecatedImageTransformModelNames.forEach((modelName) => {
    googleLlmBaseApiUrls.push(
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':generateContent',
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':streamGenerateContent',
    );
  });

  const pendingFetchResolvers = {};
  let nextPromiseId = 0;

  function handleStringInput(input, optionsArgument) {
    const actualUrl = input;
    const fetchCallArgs = [actualUrl, optionsArgument];
    const effectiveOptions = optionsArgument || {};
    const bodyForApiKeyCheck = effectiveOptions.body;
    const bodyForPostMessage = effectiveOptions.body;
    return { actualUrl, fetchCallArgs, effectiveOptions, bodyForApiKeyCheck, bodyForPostMessage };
  }

  function handleRequestInput(input, optionsArgument) {
    const actualUrl = input.url;
    const fetchCallArgs = [input, optionsArgument];
    const effectiveOptions = { method: input.method, headers: new Headers(input.headers) };
    let bodyForApiKeyCheck;
    let bodyForPostMessage;

    if (optionsArgument) {
      if (optionsArgument.method) effectiveOptions.method = optionsArgument.method;
      if (optionsArgument.headers) effectiveOptions.headers = new Headers(optionsArgument.headers);
      if ('body' in optionsArgument) {
        bodyForApiKeyCheck = optionsArgument.body;
        bodyForPostMessage = optionsArgument.body;
      } else {
        bodyForApiKeyCheck = undefined;
        bodyForPostMessage = input.body;
      }
    } else {
      bodyForApiKeyCheck = undefined;
      bodyForPostMessage = input.body;
    }
    return { actualUrl, fetchCallArgs, effectiveOptions, bodyForApiKeyCheck, bodyForPostMessage };
  }

  window.fetch = function(input, optionsArgument) {
    let actualUrl;
    let fetchCallArgs;
    let effectiveOptions = {};
    let bodyForApiKeyCheck;
    let bodyForPostMessage;

    if (typeof input === 'string') {
      ({actualUrl, fetchCallArgs, effectiveOptions, bodyForApiKeyCheck, bodyForPostMessage} = handleStringInput(input, optionsArgument));
    } else if (input instanceof Request) {
      ({actualUrl, fetchCallArgs, effectiveOptions, bodyForApiKeyCheck, bodyForPostMessage} = handleRequestInput(input, optionsArgument));
    } else {
      return originalFetch.apply(window, [input, optionsArgument]);
    }

    effectiveOptions.method = effectiveOptions.method || 'GET';
    if (!effectiveOptions.headers) {
      effectiveOptions.headers = new Headers();
    }


    if (typeof actualUrl === 'string' && googleLlmBaseApiUrls.some((url) => actualUrl.startsWith(url))) {
      let apiKeyIsNull = true;

      const regex = new RegExp("models/([^:]+)");
      const modelNameMatch = actualUrl.match(regex);
      const modelName = modelNameMatch ? modelNameMatch[1] : 'unspecified';


      try {
        const urlObject = new URL(actualUrl);  // Use URL object for robust parsing
        const apiKeyParam = urlObject.searchParams.get('key');
        if (apiKeyParam) {
          apiKeyIsNull = false;
        }
      } catch (e) {
        // Continue checks even if URL parsing fails
      }

      if (apiKeyIsNull && effectiveOptions.headers) {
        const h = new Headers(effectiveOptions.headers);
        const apiKeyHeaderValue = h.get('X-API-Key') || h.get('x-api-key');
        if (apiKeyHeaderValue) {
          apiKeyIsNull = false;
          return originalFetch.apply(window, fetchCallArgs);
        }
      }

      if (apiKeyIsNull && effectiveOptions.method && ['POST', 'PUT', 'PATCH'].includes(effectiveOptions.method.toUpperCase()) && typeof bodyForApiKeyCheck === 'string') {
        try {
          const bodyData = JSON.parse(bodyForApiKeyCheck);
          if (bodyData && bodyData.apiKey) {
            apiKeyIsNull = false;
            return originalFetch.apply(window, fetchCallArgs);
          }
        } catch (e) {
          // Ignore JSON parsing errors
        }
      }

      if(apiKeyIsNull) {
        const promiseId = nextPromiseId++;
        const promise = new Promise((resolve) => {
          pendingFetchResolvers[promiseId] = (resolvedResponse) => {
            delete pendingFetchResolvers[promiseId];
            resolve(resolvedResponse);
          };
        });

        let serializedBodyForPostMessage;
        if (typeof bodyForPostMessage === 'string' || bodyForPostMessage == null) {
            serializedBodyForPostMessage = bodyForPostMessage;
        } else if (bodyForPostMessage instanceof ReadableStream) {
            serializedBodyForPostMessage = null;
        } else {
            try {
                serializedBodyForPostMessage = JSON.stringify(bodyForPostMessage);
            } catch (e) {
                serializedBodyForPostMessage = null;
            }
        }

        const messageOptions = {
            method: effectiveOptions.method,
            headers: Object.fromEntries(new Headers(effectiveOptions.headers).entries()),
            body: serializedBodyForPostMessage
        };

        window.parent.postMessage({
          type: 'requestFetch',
          url: actualUrl,
          modelName: modelName,
          options: messageOptions,
          promiseId: promiseId,
        }, '*');

        return promise;
      }
      return originalFetch.apply(window, fetchCallArgs);
    }
    return originalFetch.apply(window, fetchCallArgs);
  };

  window.addEventListener('message', function(event) {
    if (event.data && event.data.type === 'resolveFetch') {
      const { promiseId, response } = event.data;
      if (pendingFetchResolvers[promiseId]) {
        try {
          const reconstructedResponse = new Response(response.body, {
            status: response.status,
            statusText: response.statusText,
            headers: new Headers(response.headers),
          });
          pendingFetchResolvers[promiseId](reconstructedResponse);
        } catch (error) {
          pendingFetchResolvers[promiseId](new Response(null, { status: 500, statusText: "Interceptor Response Reconstruction Error" }));
        }
      }
    }
  });

}))({"textModelName":"gemini-3-flash-preview","imageModelName":"imagen-4.0-generate-001","imageEditModelName":"gemini-3.1-flash-image","imageTransformModelName":"gemini-3-pro-image","videoModelName":"veo-2.0-generate-001","ttsModelName":"gemini-2.5-flash-preview-tts","deprecatedTextModelNames":["gemini-2.0-flash","gemini-2.5-flash","gemini-2.5-flash-preview-04-17","gemini-2.5-flash-preview-05-20","gemini-2.5-flash-preview-09-2025"],"deprecatedImageModelNames":["imagen-3.0-generate-001","imagen-3.0-generate-002"],"deprecatedGenerateImageModelNames":["gemini-2.5-flash-image-preview","gemini-2.5-flash-image","gemini-3.1-flash-image-preview"],"deprecatedImageTransformModelNames":["gemini-3-pro-image-preview-11-2025"]})</script><script data-bard-client-injected="true">(function(){'use strict';function a(){window.parent.postMessage({type:"interaction"},"*")}window.addEventListener("click",a,{capture:!0,passive:!0});window.addEventListener("touchstart",a,{capture:!0,passive:!0});window.addEventListener("keydown",a,{capture:!0,passive:!0});}).call(this);
</script><script data-bard-client-injected="true">(function() {
  const originalConsoleLog = console.log;
  const originalConsoleError = console.error;

    /**
   * Normalizes an error event or a promise rejection reason into a structured error object.
   * @param {*} errorEventOrReason The error object or reason.
   * @return {object} Structured error data { message, name, stack }.
   */
  function getErrorObject(errorEventOrReason) {
    if (errorEventOrReason instanceof Error) {
      return {
        message: errorEventOrReason.message,
        name: errorEventOrReason.name,
        stack: errorEventOrReason.stack,
      };
    }
    // Fallback for non-Error objects.
    try {
      return {
        message: JSON.stringify(errorEventOrReason),
        name: 'UnknownErrorType',
        stack: null,
      };
    } catch (e) {
      return {
        message: String(errorEventOrReason),
        name: 'UnknownErrorTypeNonStringifiable',
        stack: null,
      };
    }
  }

  /**
   * Converts an array of arguments (from log/error) into a single string.
   * Handles Error objects specially to include their message and stack.
   * @param {Array<*>} args - Arguments passed to console methods.
   * @return {string} A string representation of the arguments.
   */
  function stringifyArgs(args) {
    return args
      .map((arg) => {
        if (arg instanceof Error) {
          const {message, stack} = arg;
          return `Error: ${message}${stack ? ('\nStack: ' + stack) : ''}`;
        }
        if (typeof arg === 'object' && arg !== null) {
          try {
            return JSON.stringify(arg);
          } catch (error) {
            return '[Circular Object]';
          }
        } else {
          return String(arg);
        }
      })
      .join(' ');
  }

  console.log = function(...args) {
    const logString = stringifyArgs(args);
    window.parent.postMessage({ type: 'log', message: logString }, '*');
    originalConsoleLog.apply(console, args);
  };

  console.error = function(...args) {
    let errorData;
    if (args.length > 0 && args[0] instanceof Error) {
      const err = args[0];
      // If the first arg is an Error, capture its details.
      errorData = {
        type: 'error',
        source: 'CONSOLE_ERROR',
        ...getErrorObject(err),
        rawArgsString: stringifyArgs(args.slice(1)),
        timestamp: new Date().toISOString(),
      };
    } else {
      // If not an Error object, treat all args as a general error message.
      errorData = {
        type: 'error',
        source: 'CONSOLE_ERROR',
        message: stringifyArgs(args),
        name: 'ConsoleLoggedError',
        stack: null,
        timestamp: new Date().toISOString(),
      };
    }
    window.parent.postMessage(errorData, '*');
    originalConsoleError.apply(console, args);
  };

  // Listen for global unhandled synchronous errors.
  window.addEventListener('error', function(event) {
    const errorDetails = event.error ? getErrorObject(event.error) : {
      message: event.message,
      name: 'GlobalError',
      stack: null,
      filename: event.filename,
      lineno: event.lineno,
      colno: event.colno,
    };

    window.parent.postMessage({
      type: 'error',
      source: 'global',
      ...errorDetails,
      message: errorDetails.message || event.message,
      timestamp: new Date().toISOString(),
    }, '*');
  });

  // Listen for unhandled promise rejections (asynchronous errors).
  window.addEventListener('unhandledrejection', function(event) {
    const errorDetails = getErrorObject(event.reason);

    window.parent.postMessage({
      type: 'error',
      source: 'unhandledrejection',
      ...errorDetails,
      message: errorDetails.message || 'Unhandled Promise Rejection',
      timestamp: new Date().toISOString(),
    }, '*');
  });

})();</script>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Duta Teknik | Spesialis Perbaikan Pompa Air &amp; Sumur Bor Profesional</title>
    <meta name="description" content="Layanan resmi teknisi panggilan spesialis perbaikan mesin pompa air, sumur bor, dan filter air bergaransi di Jakarta Selatan dan Tangerang Selatan. Hubungi 088985105537.">
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Google Fonts: Plus Jakarta Sans -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="">
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&amp;display=swap" rel="stylesheet">
    
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        korporat: {
                            900: '#0F172A',
                            800: '#1E293B',
                            700: '#334155',
                            biru: '#0284C7',
                            emas: '#D97706',
                            hijau: '#059669'
                        }
                    },
                    fontFamily: {
                        sans: ['Plus Jakarta Sans', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    
    <style>
        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
            background-color: #F8FAFC;
            color: #0F172A;
        }
        .bayangan-elegan {
            box-shadow: 0 10px 25px -5px rgba(15, 23, 42, 0.08), 0 8px 10px -6px rgba(15, 23, 42, 0.08);
        }
        .kartu-pro {
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }
        .kartu-pro:hover {
            transform: translateY(-4px);
            box-shadow: 0 20px 35px -10px rgba(2, 132, 199, 0.12);
            border-color: #0284C7;
        }
    </style>
<style>*, ::before, ::after{--tw-border-spacing-x:0;--tw-border-spacing-y:0;--tw-translate-x:0;--tw-translate-y:0;--tw-rotate:0;--tw-skew-x:0;--tw-skew-y:0;--tw-scale-x:1;--tw-scale-y:1;--tw-pan-x: ;--tw-pan-y: ;--tw-pinch-zoom: ;--tw-scroll-snap-strictness:proximity;--tw-gradient-from-position: ;--tw-gradient-via-position: ;--tw-gradient-to-position: ;--tw-ordinal: ;--tw-slashed-zero: ;--tw-numeric-figure: ;--tw-numeric-spacing: ;--tw-numeric-fraction: ;--tw-ring-inset: ;--tw-ring-offset-width:0px;--tw-ring-offset-color:#fff;--tw-ring-color:rgb(59 130 246 / 0.5);--tw-ring-offset-shadow:0 0 #0000;--tw-ring-shadow:0 0 #0000;--tw-shadow:0 0 #0000;--tw-shadow-colored:0 0 #0000;--tw-blur: ;--tw-brightness: ;--tw-contrast: ;--tw-grayscale: ;--tw-hue-rotate: ;--tw-invert: ;--tw-saturate: ;--tw-sepia: ;--tw-drop-shadow: ;--tw-backdrop-blur: ;--tw-backdrop-brightness: ;--tw-backdrop-contrast: ;--tw-backdrop-grayscale: ;--tw-backdrop-hue-rotate: ;--tw-backdrop-invert: ;--tw-backdrop-opacity: ;--tw-backdrop-saturate: ;--tw-backdrop-sepia: ;--tw-contain-size: ;--tw-contain-layout: ;--tw-contain-paint: ;--tw-contain-style: }::backdrop{--tw-border-spacing-x:0;--tw-border-spacing-y:0;--tw-translate-x:0;--tw-translate-y:0;--tw-rotate:0;--tw-skew-x:0;--tw-skew-y:0;--tw-scale-x:1;--tw-scale-y:1;--tw-pan-x: ;--tw-pan-y: ;--tw-pinch-zoom: ;--tw-scroll-snap-strictness:proximity;--tw-gradient-from-position: ;--tw-gradient-via-position: ;--tw-gradient-to-position: ;--tw-ordinal: ;--tw-slashed-zero: ;--tw-numeric-figure: ;--tw-numeric-spacing: ;--tw-numeric-fraction: ;--tw-ring-inset: ;--tw-ring-offset-width:0px;--tw-ring-offset-color:#fff;--tw-ring-color:rgb(59 130 246 / 0.5);--tw-ring-offset-shadow:0 0 #0000;--tw-ring-shadow:0 0 #0000;--tw-shadow:0 0 #0000;--tw-shadow-colored:0 0 #0000;--tw-blur: ;--tw-brightness: ;--tw-contrast: ;--tw-grayscale: ;--tw-hue-rotate: ;--tw-invert: ;--tw-saturate: ;--tw-sepia: ;--tw-drop-shadow: ;--tw-backdrop-blur: ;--tw-backdrop-brightness: ;--tw-backdrop-contrast: ;--tw-backdrop-grayscale: ;--tw-backdrop-hue-rotate: ;--tw-backdrop-invert: ;--tw-backdrop-opacity: ;--tw-backdrop-saturate: ;--tw-backdrop-sepia: ;--tw-contain-size: ;--tw-contain-layout: ;--tw-contain-paint: ;--tw-contain-style: }/* ! tailwindcss v3.4.17 | MIT License | https://tailwindcss.com */*,::after,::before{box-sizing:border-box;border-width:0;border-style:solid;border-color:#e5e7eb}::after,::before{--tw-content:''}:host,html{line-height:1.5;-webkit-text-size-adjust:100%;-moz-tab-size:4;tab-size:4;font-family:Plus Jakarta Sans, sans-serif;font-feature-settings:normal;font-variation-settings:normal;-webkit-tap-highlight-color:transparent}body{margin:0;line-height:inherit}hr{height:0;color:inherit;border-top-width:1px}abbr:where([title]){-webkit-text-decoration:underline dotted;text-decoration:underline dotted}h1,h2,h3,h4,h5,h6{font-size:inherit;font-weight:inherit}a{color:inherit;text-decoration:inherit}b,strong{font-weight:bolder}code,kbd,pre,samp{font-family:ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;font-feature-settings:normal;font-variation-settings:normal;font-size:1em}small{font-size:80%}sub,sup{font-size:75%;line-height:0;position:relative;vertical-align:baseline}sub{bottom:-.25em}sup{top:-.5em}table{text-indent:0;border-color:inherit;border-collapse:collapse}button,input,optgroup,select,textarea{font-family:inherit;font-feature-settings:inherit;font-variation-settings:inherit;font-size:100%;font-weight:inherit;line-height:inherit;letter-spacing:inherit;color:inherit;margin:0;padding:0}button,select{text-transform:none}button,input:where([type=button]),input:where([type=reset]),input:where([type=submit]){-webkit-appearance:button;background-color:transparent;background-image:none}:-moz-focusring{outline:auto}:-moz-ui-invalid{box-shadow:none}progress{vertical-align:baseline}::-webkit-inner-spin-button,::-webkit-outer-spin-button{height:auto}[type=search]{-webkit-appearance:textfield;outline-offset:-2px}::-webkit-search-decoration{-webkit-appearance:none}::-webkit-file-upload-button{-webkit-appearance:button;font:inherit}summary{display:list-item}blockquote,dd,dl,figure,h1,h2,h3,h4,h5,h6,hr,p,pre{margin:0}fieldset{margin:0;padding:0}legend{padding:0}menu,ol,ul{list-style:none;margin:0;padding:0}dialog{padding:0}textarea{resize:vertical}input::placeholder,textarea::placeholder{opacity:1;color:#9ca3af}[role=button],button{cursor:pointer}:disabled{cursor:default}audio,canvas,embed,iframe,img,object,svg,video{display:block;vertical-align:middle}img,video{max-width:100%;height:auto}[hidden]:where(:not([hidden=until-found])){display:none}.fixed{position:fixed}.absolute{position:absolute}.relative{position:relative}.sticky{position:sticky}.inset-0{inset:0px}.bottom-0{bottom:0px}.left-0{left:0px}.right-0{right:0px}.top-0{top:0px}.z-10{z-index:10}.z-50{z-index:50}.mx-auto{margin-left:auto;margin-right:auto}.mb-12{margin-bottom:3rem}.mb-16{margin-bottom:4rem}.mb-2{margin-bottom:0.5rem}.mb-4{margin-bottom:1rem}.mb-5{margin-bottom:1.25rem}.mb-6{margin-bottom:1.5rem}.mr-1\.5{margin-right:0.375rem}.mt-1{margin-top:0.25rem}.mt-1\.5{margin-top:0.375rem}.mt-2{margin-top:0.5rem}.mt-3{margin-top:0.75rem}.mt-4{margin-top:1rem}.block{display:block}.inline-block{display:inline-block}.flex{display:flex}.inline-flex{display:inline-flex}.grid{display:grid}.hidden{display:none}.h-11{height:2.75rem}.h-12{height:3rem}.h-14{height:3.5rem}.h-2{height:0.5rem}.h-20{height:5rem}.h-8{height:2rem}.h-9{height:2.25rem}.w-11{width:2.75rem}.w-12{width:3rem}.w-14{width:3.5rem}.w-2{width:0.5rem}.w-8{width:2rem}.w-9{width:2.25rem}.w-full{width:100%}.max-w-2xl{max-width:42rem}.max-w-3xl{max-width:48rem}.max-w-7xl{max-width:80rem}.max-w-sm{max-width:24rem}@keyframes pulse{50%{opacity:.5}}.animate-pulse{animation:pulse 2s cubic-bezier(0.4, 0, 0.6, 1) infinite}.cursor-pointer{cursor:pointer}.grid-cols-2{grid-template-columns:repeat(2, minmax(0, 1fr))}.flex-col{flex-direction:column}.items-center{align-items:center}.justify-center{justify-content:center}.justify-between{justify-content:space-between}.gap-1\.5{gap:0.375rem}.gap-10{gap:2.5rem}.gap-12{gap:3rem}.gap-2{gap:0.5rem}.gap-2\.5{gap:0.625rem}.gap-3{gap:0.75rem}.gap-3\.5{gap:0.875rem}.gap-4{gap:1rem}.gap-8{gap:2rem}.space-y-2\.5 > :not([hidden]) ~ :not([hidden]){--tw-space-y-reverse:0;margin-top:calc(0.625rem * calc(1 - var(--tw-space-y-reverse)));margin-bottom:calc(0.625rem * var(--tw-space-y-reverse))}.space-y-3 > :not([hidden]) ~ :not([hidden]){--tw-space-y-reverse:0;margin-top:calc(0.75rem * calc(1 - var(--tw-space-y-reverse)));margin-bottom:calc(0.75rem * var(--tw-space-y-reverse))}.space-y-4 > :not([hidden]) ~ :not([hidden]){--tw-space-y-reverse:0;margin-top:calc(1rem * calc(1 - var(--tw-space-y-reverse)));margin-bottom:calc(1rem * var(--tw-space-y-reverse))}.space-y-6 > :not([hidden]) ~ :not([hidden]){--tw-space-y-reverse:0;margin-top:calc(1.5rem * calc(1 - var(--tw-space-y-reverse)));margin-bottom:calc(1.5rem * var(--tw-space-y-reverse))}.overflow-hidden{overflow:hidden}.scroll-smooth{scroll-behavior:smooth}.rounded-2xl{border-radius:1rem}.rounded-3xl{border-radius:1.5rem}.rounded-full{border-radius:9999px}.rounded-lg{border-radius:0.5rem}.rounded-xl{border-radius:0.75rem}.border{border-width:1px}.border-b{border-bottom-width:1px}.border-t{border-top-width:1px}.border-amber-200{--tw-border-opacity:1;border-color:rgb(253 230 138 / var(--tw-border-opacity, 1))}.border-emerald-100{--tw-border-opacity:1;border-color:rgb(209 250 229 / var(--tw-border-opacity, 1))}.border-sky-100{--tw-border-opacity:1;border-color:rgb(224 242 254 / var(--tw-border-opacity, 1))}.border-slate-100{--tw-border-opacity:1;border-color:rgb(241 245 249 / var(--tw-border-opacity, 1))}.border-slate-200{--tw-border-opacity:1;border-color:rgb(226 232 240 / var(--tw-border-opacity, 1))}.border-slate-300{--tw-border-opacity:1;border-color:rgb(203 213 225 / var(--tw-border-opacity, 1))}.border-slate-700{--tw-border-opacity:1;border-color:rgb(51 65 85 / var(--tw-border-opacity, 1))}.border-slate-800{--tw-border-opacity:1;border-color:rgb(30 41 59 / var(--tw-border-opacity, 1))}.border-white\/15{border-color:rgb(255 255 255 / 0.15)}.border-white\/20{border-color:rgb(255 255 255 / 0.2)}.bg-amber-100{--tw-bg-opacity:1;background-color:rgb(254 243 199 / var(--tw-bg-opacity, 1))}.bg-amber-50{--tw-bg-opacity:1;background-color:rgb(255 251 235 / var(--tw-bg-opacity, 1))}.bg-amber-600{--tw-bg-opacity:1;background-color:rgb(217 119 6 / var(--tw-bg-opacity, 1))}.bg-emerald-100{--tw-bg-opacity:1;background-color:rgb(209 250 229 / var(--tw-bg-opacity, 1))}.bg-emerald-400{--tw-bg-opacity:1;background-color:rgb(52 211 153 / var(--tw-bg-opacity, 1))}.bg-emerald-50{--tw-bg-opacity:1;background-color:rgb(236 253 245 / var(--tw-bg-opacity, 1))}.bg-emerald-500{--tw-bg-opacity:1;background-color:rgb(16 185 129 / var(--tw-bg-opacity, 1))}.bg-emerald-600{--tw-bg-opacity:1;background-color:rgb(5 150 105 / var(--tw-bg-opacity, 1))}.bg-sky-100{--tw-bg-opacity:1;background-color:rgb(224 242 254 / var(--tw-bg-opacity, 1))}.bg-sky-50{--tw-bg-opacity:1;background-color:rgb(240 249 255 / var(--tw-bg-opacity, 1))}.bg-sky-600{--tw-bg-opacity:1;background-color:rgb(2 132 199 / var(--tw-bg-opacity, 1))}.bg-slate-100{--tw-bg-opacity:1;background-color:rgb(241 245 249 / var(--tw-bg-opacity, 1))}.bg-slate-50{--tw-bg-opacity:1;background-color:rgb(248 250 252 / var(--tw-bg-opacity, 1))}.bg-slate-800{--tw-bg-opacity:1;background-color:rgb(30 41 59 / var(--tw-bg-opacity, 1))}.bg-slate-900{--tw-bg-opacity:1;background-color:rgb(15 23 42 / var(--tw-bg-opacity, 1))}.bg-white{--tw-bg-opacity:1;background-color:rgb(255 255 255 / var(--tw-bg-opacity, 1))}.bg-white\/10{background-color:rgb(255 255 255 / 0.1)}.bg-white\/95{background-color:rgb(255 255 255 / 0.95)}.bg-\[radial-gradient\(\#38bdf8_1px\2c transparent_1px\)\]{background-image:radial-gradient(#38bdf8 1px,transparent 1px)}.bg-gradient-to-br{background-image:linear-gradient(to bottom right, var(--tw-gradient-stops))}.from-slate-900{--tw-gradient-from:#0f172a var(--tw-gradient-from-position);--tw-gradient-to:rgb(15 23 42 / 0) var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), var(--tw-gradient-to)}.via-slate-800{--tw-gradient-to:rgb(30 41 59 / 0)  var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), #1e293b var(--tw-gradient-via-position), var(--tw-gradient-to)}.to-slate-900{--tw-gradient-to:#0f172a var(--tw-gradient-to-position)}.p-2{padding:0.5rem}.p-3{padding:0.75rem}.p-3\.5{padding:0.875rem}.p-4{padding:1rem}.p-6{padding:1.5rem}.p-8{padding:2rem}.px-3\.5{padding-left:0.875rem;padding-right:0.875rem}.px-4{padding-left:1rem;padding-right:1rem}.px-5{padding-left:1.25rem;padding-right:1.25rem}.px-6{padding-left:1.5rem;padding-right:1.5rem}.px-7{padding-left:1.75rem;padding-right:1.75rem}.py-1{padding-top:0.25rem;padding-bottom:0.25rem}.py-1\.5{padding-top:0.375rem;padding-bottom:0.375rem}.py-14{padding-top:3.5rem;padding-bottom:3.5rem}.py-16{padding-top:4rem;padding-bottom:4rem}.py-2{padding-top:0.5rem;padding-bottom:0.5rem}.py-2\.5{padding-top:0.625rem;padding-bottom:0.625rem}.py-20{padding-top:5rem;padding-bottom:5rem}.py-3{padding-top:0.75rem;padding-bottom:0.75rem}.py-3\.5{padding-top:0.875rem;padding-bottom:0.875rem}.py-4{padding-top:1rem;padding-bottom:1rem}.pb-28{padding-bottom:7rem}.pb-4{padding-bottom:1rem}.pt-2{padding-top:0.5rem}.pt-4{padding-top:1rem}.pt-8{padding-top:2rem}.text-left{text-align:left}.text-center{text-align:center}.text-2xl{font-size:1.5rem;line-height:2rem}.text-3xl{font-size:1.875rem;line-height:2.25rem}.text-4xl{font-size:2.25rem;line-height:2.5rem}.text-\[10px\]{font-size:10px}.text-\[11px\]{font-size:11px}.text-base{font-size:1rem;line-height:1.5rem}.text-lg{font-size:1.125rem;line-height:1.75rem}.text-sm{font-size:0.875rem;line-height:1.25rem}.text-xl{font-size:1.25rem;line-height:1.75rem}.text-xs{font-size:0.75rem;line-height:1rem}.font-bold{font-weight:700}.font-extrabold{font-weight:800}.font-light{font-weight:300}.font-semibold{font-weight:600}.uppercase{text-transform:uppercase}.leading-none{line-height:1}.leading-relaxed{line-height:1.625}.leading-tight{line-height:1.25}.tracking-tight{letter-spacing:-0.025em}.tracking-wider{letter-spacing:0.05em}.tracking-widest{letter-spacing:0.1em}.text-amber-400{--tw-text-opacity:1;color:rgb(251 191 36 / var(--tw-text-opacity, 1))}.text-amber-600{--tw-text-opacity:1;color:rgb(217 119 6 / var(--tw-text-opacity, 1))}.text-emerald-600{--tw-text-opacity:1;color:rgb(5 150 105 / var(--tw-text-opacity, 1))}.text-emerald-700{--tw-text-opacity:1;color:rgb(4 120 87 / var(--tw-text-opacity, 1))}.text-sky-300{--tw-text-opacity:1;color:rgb(125 211 252 / var(--tw-text-opacity, 1))}.text-sky-400{--tw-text-opacity:1;color:rgb(56 189 248 / var(--tw-text-opacity, 1))}.text-sky-600{--tw-text-opacity:1;color:rgb(2 132 199 / var(--tw-text-opacity, 1))}.text-sky-700{--tw-text-opacity:1;color:rgb(3 105 161 / var(--tw-text-opacity, 1))}.text-slate-300{--tw-text-opacity:1;color:rgb(203 213 225 / var(--tw-text-opacity, 1))}.text-slate-400{--tw-text-opacity:1;color:rgb(148 163 184 / var(--tw-text-opacity, 1))}.text-slate-500{--tw-text-opacity:1;color:rgb(100 116 139 / var(--tw-text-opacity, 1))}.text-slate-600{--tw-text-opacity:1;color:rgb(71 85 105 / var(--tw-text-opacity, 1))}.text-slate-700{--tw-text-opacity:1;color:rgb(51 65 85 / var(--tw-text-opacity, 1))}.text-slate-800{--tw-text-opacity:1;color:rgb(30 41 59 / var(--tw-text-opacity, 1))}.text-slate-900{--tw-text-opacity:1;color:rgb(15 23 42 / var(--tw-text-opacity, 1))}.text-slate-950{--tw-text-opacity:1;color:rgb(2 6 23 / var(--tw-text-opacity, 1))}.text-white{--tw-text-opacity:1;color:rgb(255 255 255 / var(--tw-text-opacity, 1))}.antialiased{-webkit-font-smoothing:antialiased;-moz-osx-font-smoothing:grayscale}.opacity-10{opacity:0.1}.opacity-50{opacity:0.5}.shadow-2xl{--tw-shadow:0 25px 50px -12px rgb(0 0 0 / 0.25);--tw-shadow-colored:0 25px 50px -12px var(--tw-shadow-color);box-shadow:var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow)}.shadow-lg{--tw-shadow:0 10px 15px -3px rgb(0 0 0 / 0.1), 0 4px 6px -4px rgb(0 0 0 / 0.1);--tw-shadow-colored:0 10px 15px -3px var(--tw-shadow-color), 0 4px 6px -4px var(--tw-shadow-color);box-shadow:var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow)}.shadow-md{--tw-shadow:0 4px 6px -1px rgb(0 0 0 / 0.1), 0 2px 4px -2px rgb(0 0 0 / 0.1);--tw-shadow-colored:0 4px 6px -1px var(--tw-shadow-color), 0 2px 4px -2px var(--tw-shadow-color);box-shadow:var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow)}.shadow-sm{--tw-shadow:0 1px 2px 0 rgb(0 0 0 / 0.05);--tw-shadow-colored:0 1px 2px 0 var(--tw-shadow-color);box-shadow:var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow)}.backdrop-blur-md{--tw-backdrop-blur:blur(12px);-webkit-backdrop-filter:var(--tw-backdrop-blur) var(--tw-backdrop-brightness) var(--tw-backdrop-contrast) var(--tw-backdrop-grayscale) var(--tw-backdrop-hue-rotate) var(--tw-backdrop-invert) var(--tw-backdrop-opacity) var(--tw-backdrop-saturate) var(--tw-backdrop-sepia);backdrop-filter:var(--tw-backdrop-blur) var(--tw-backdrop-brightness) var(--tw-backdrop-contrast) var(--tw-backdrop-grayscale) var(--tw-backdrop-hue-rotate) var(--tw-backdrop-invert) var(--tw-backdrop-opacity) var(--tw-backdrop-saturate) var(--tw-backdrop-sepia)}.backdrop-blur-sm{--tw-backdrop-blur:blur(4px);-webkit-backdrop-filter:var(--tw-backdrop-blur) var(--tw-backdrop-brightness) var(--tw-backdrop-contrast) var(--tw-backdrop-grayscale) var(--tw-backdrop-hue-rotate) var(--tw-backdrop-invert) var(--tw-backdrop-opacity) var(--tw-backdrop-saturate) var(--tw-backdrop-sepia);backdrop-filter:var(--tw-backdrop-blur) var(--tw-backdrop-brightness) var(--tw-backdrop-contrast) var(--tw-backdrop-grayscale) var(--tw-backdrop-hue-rotate) var(--tw-backdrop-invert) var(--tw-backdrop-opacity) var(--tw-backdrop-saturate) var(--tw-backdrop-sepia)}.transition-all{transition-property:all;transition-timing-function:cubic-bezier(0.4, 0, 0.2, 1);transition-duration:150ms}.transition-colors{transition-property:color, background-color, border-color, fill, stroke, -webkit-text-decoration-color;transition-property:color, background-color, border-color, text-decoration-color, fill, stroke;transition-property:color, background-color, border-color, text-decoration-color, fill, stroke, -webkit-text-decoration-color;transition-timing-function:cubic-bezier(0.4, 0, 0.2, 1);transition-duration:150ms}.transition-transform{transition-property:transform;transition-timing-function:cubic-bezier(0.4, 0, 0.2, 1);transition-duration:150ms}.duration-200{transition-duration:200ms}.\[background-size\:16px_16px\]{background-size:16px 16px}.hover\:border-sky-600:hover{--tw-border-opacity:1;border-color:rgb(2 132 199 / var(--tw-border-opacity, 1))}.hover\:bg-amber-700:hover{--tw-bg-opacity:1;background-color:rgb(180 83 9 / var(--tw-bg-opacity, 1))}.hover\:bg-emerald-600:hover{--tw-bg-opacity:1;background-color:rgb(5 150 105 / var(--tw-bg-opacity, 1))}.hover\:bg-emerald-700:hover{--tw-bg-opacity:1;background-color:rgb(4 120 87 / var(--tw-bg-opacity, 1))}.hover\:bg-sky-50\/50:hover{background-color:rgb(240 249 255 / 0.5)}.hover\:bg-slate-200:hover{--tw-bg-opacity:1;background-color:rgb(226 232 240 / var(--tw-bg-opacity, 1))}.hover\:bg-white\/20:hover{background-color:rgb(255 255 255 / 0.2)}.hover\:text-sky-600:hover{--tw-text-opacity:1;color:rgb(2 132 199 / var(--tw-text-opacity, 1))}.hover\:text-sky-700:hover{--tw-text-opacity:1;color:rgb(3 105 161 / var(--tw-text-opacity, 1))}.hover\:text-white:hover{--tw-text-opacity:1;color:rgb(255 255 255 / var(--tw-text-opacity, 1))}.hover\:underline:hover{-webkit-text-decoration-line:underline;text-decoration-line:underline}.group[open] .group-open\:-rotate-180{--tw-rotate:-180deg;transform:translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y))}.group:hover .group-hover\:text-sky-600{--tw-text-opacity:1;color:rgb(2 132 199 / var(--tw-text-opacity, 1))}@media (min-width: 640px){.sm\:mt-0{margin-top:0px}.sm\:flex{display:flex}.sm\:w-auto{width:auto}.sm\:flex-row{flex-direction:row}.sm\:items-center{align-items:center}.sm\:justify-between{justify-content:space-between}.sm\:p-8{padding:2rem}.sm\:px-6{padding-left:1.5rem;padding-right:1.5rem}.sm\:text-left{text-align:left}.sm\:text-3xl{font-size:1.875rem;line-height:2.25rem}.sm\:text-5xl{font-size:3rem;line-height:1}.sm\:text-base{font-size:1rem;line-height:1.5rem}.sm\:text-sm{font-size:0.875rem;line-height:1.25rem}}@media (min-width: 768px){.md\:col-span-2{grid-column:span 2 / span 2}.md\:hidden{display:none}.md\:grid-cols-2{grid-template-columns:repeat(2, minmax(0, 1fr))}.md\:grid-cols-3{grid-template-columns:repeat(3, minmax(0, 1fr))}.md\:grid-cols-4{grid-template-columns:repeat(4, minmax(0, 1fr))}.md\:pb-0{padding-bottom:0px}}@media (min-width: 1024px){.lg\:col-span-5{grid-column:span 5 / span 5}.lg\:col-span-7{grid-column:span 7 / span 7}.lg\:flex{display:flex}.lg\:hidden{display:none}.lg\:grid-cols-12{grid-template-columns:repeat(12, minmax(0, 1fr))}.lg\:grid-cols-3{grid-template-columns:repeat(3, minmax(0, 1fr))}.lg\:px-8{padding-left:2rem;padding-right:2rem}.lg\:py-24{padding-top:6rem;padding-bottom:6rem}}.\[\&_summary\:\:-webkit-details-marker\]\:hidden summary::-webkit-details-marker{display:none}</style></head>
<body class="antialiased pb-28 md:pb-0">

    <!-- Kotak Khusus Pengguna HP untuk Menyalin HTML -->
    <div class="bg-amber-50 border-b border-amber-200 p-4 text-slate-800 text-xs">
        <div class="max-w-7xl mx-auto flex flex-col sm:flex-row items-center justify-between gap-3">
            <div class="flex items-center gap-2 text-center sm:text-left">
                <i class="fa-solid fa-mobile-screen-button text-amber-600 text-base"></i>
                <span><strong>Pengguna HP:</strong> Jika sulit menyalin, gunakan tombol di samping untuk menyalin seluruh kode HTML ke clipboard Anda.</span>
            </div>
            <button onclick="salinKodePonsel()" class="w-full sm:w-auto bg-amber-600 hover:bg-amber-700 text-white font-extrabold px-4 py-2.5 rounded-xl shadow-sm transition-all flex items-center justify-center gap-2">
                <i class="fa-solid fa-copy"></i>
                <span id="teksTombolSalin">Salin Kode HTML</span>
            </button>
        </div>
    </div>

    <div class="bg-slate-900 text-slate-300 text-xs py-2.5 px-4 border-b border-slate-800">
        <div class="max-w-7xl mx-auto flex flex-col sm:flex-row justify-between items-center gap-2">
            <div class="flex items-center gap-2">
                <span class="w-2 h-2 rounded-full bg-emerald-400 inline-block animate-pulse"></span>
                <span>Teknisi Siaga Panggilan Hari Ini di Jakarta Selatan &amp; Tangerang Selatan</span>
            </div>
            <div class="flex items-center gap-4">
                <span><i class="fa-solid fa-phone text-sky-400 mr-1.5"></i> Respon Cepat WhatsApp: <strong class="text-white">0889-8510-5537</strong></span>
            </div>
        </div>
    </div>

    <header class="sticky top-0 z-50 bg-white/95 backdrop-blur-md border-b border-slate-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-20">
                <a href="#" class="flex items-center gap-3">
                    <div class="w-11 h-11 rounded-xl bg-slate-900 text-sky-400 flex items-center justify-center text-xl font-extrabold shadow-md">
                        <i class="fa-solid fa-water"></i>
                    </div>
                    <div>
                        <span class="text-base font-extrabold tracking-tight text-slate-900 block leading-none">
                            DUTA <span class="text-sky-600">TEKNIK</span>
                        </span>
                        <span class="text-[10px] font-bold text-slate-500 uppercase tracking-widest block mt-1">Spesialis Pompa Air &amp; Sumur Bor</span>
                    </div>
                </a>

                <nav class="hidden lg:flex items-center gap-8 text-xs font-bold text-slate-700 uppercase tracking-wider">
                    <a href="#layanan" class="hover:text-sky-600 transition-colors">Layanan</a>
                    <a href="#keunggulan" class="hover:text-sky-600 transition-colors">Keunggulan</a>
                    <a href="#wilayah" class="hover:text-sky-600 transition-colors">Wilayah Kerja</a>
                    <a href="#tahapan" class="hover:text-sky-600 transition-colors">Cara Kerja</a>
                    <a href="#faq" class="hover:text-sky-600 transition-colors">Tanya Jawab</a>
                </nav>

                <div class="hidden sm:flex items-center gap-3">
                    <button onclick="salinKodeHtml()" class="inline-flex items-center gap-1.5 bg-slate-100 hover:bg-slate-200 text-slate-800 font-bold text-xs px-4 py-3 rounded-xl transition-all border border-slate-300">
                        <i class="fa-solid fa-download"></i>
                        <span>Download HTML</span>
                    </button>
                    <a href="https://wa.me/6288985105537?text=Selamat%20siang%20Duta%20Teknik,%20saya%20ingin%20berkonsultasi%20mengenai%20perbaikan%20pompa%20air." target="_blank" class="inline-flex items-center gap-2 bg-emerald-600 hover:bg-emerald-700 text-white font-bold text-xs px-5 py-3 rounded-xl transition-all shadow-md">
                        <i class="fa-brands fa-whatsapp text-base"></i>
                        <span>WHATSAPP KAMI</span>
                    </a>
                </div>

                <button id="tombolMenu" aria-label="Menu" class="lg:hidden p-2 text-slate-800">
                    <i class="fa-solid fa-bars text-xl"></i>
                </button>
            </div>
        </div>

        <div id="menuPonsel" class="hidden lg:hidden bg-white border-b border-slate-200 px-6 py-4 space-y-3">
            <a href="#layanan" class="block text-slate-800 font-semibold text-sm py-1">Layanan</a>
            <a href="#keunggulan" class="block text-slate-800 font-semibold text-sm py-1">Keunggulan</a>
            <a href="#wilayah" class="block text-slate-800 font-semibold text-sm py-1">Wilayah Kerja</a>
            <a href="#tahapan" class="block text-slate-800 font-semibold text-sm py-1">Cara Kerja</a>
            <a href="#faq" class="block text-slate-800 font-semibold text-sm py-1">Tanya Jawab</a>
            <button onclick="salinKodeHtml()" class="w-full flex items-center justify-center gap-2 bg-slate-100 text-slate-800 font-bold py-3 rounded-xl text-xs border border-slate-300">
                <i class="fa-solid fa-download"></i>
                <span>Download Kode HTML</span>
            </button>
            <a href="https://wa.me/6288985105537?text=Selamat%20siang%20Duta%20Teknik,%20saya%20ingin%20berkonsultasi%20mengenai%20perbaikan%20pompa%20air." target="_blank" class="w-full flex items-center justify-center gap-2 bg-emerald-600 text-white font-bold py-3 rounded-xl text-xs mt-2 shadow-sm">
                <i class="fa-brands fa-whatsapp text-base"></i>
                <span>Hubungi WhatsApp</span>
            </a>
        </div>
    </header>

    <section class="bg-gradient-to-br from-slate-900 via-slate-800 to-slate-900 text-white py-16 lg:py-24 relative overflow-hidden">
        <div class="absolute inset-0 opacity-10 bg-[radial-gradient(#38bdf8_1px,transparent_1px)] [background-size:16px_16px]"></div>
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="grid lg:grid-cols-12 gap-12 items-center">
                <div class="lg:col-span-7 space-y-6">
                    <div class="inline-flex items-center gap-2 bg-white/10 border border-white/15 px-4 py-2 rounded-full text-sky-300 text-xs font-semibold backdrop-blur-sm">
                        <i class="fa-solid fa-award text-amber-400"></i>
                        <span>Jasa Teknisi Spesialis Pompa Air &amp; Sumur Bor Bergaransi Resmi</span>
                    </div>

                    <h1 class="text-3xl sm:text-5xl font-extrabold tracking-tight leading-tight">
                        Solusi Profesional Masalah Air &amp; <span class="text-sky-400">Pompa Rusak</span> di Rumah Anda
                    </h1>

                    <p class="text-slate-300 text-sm sm:text-base leading-relaxed font-light max-w-2xl">
                        Melayani perbaikan mesin pompa air segala merek, pembuatan sumur bor baru, dan instalasi filter air bersih dengan teknisi berpengalaman yang langsung datang ke lokasi Anda di wilayah Jakarta Selatan dan Tangerang Selatan.
                    </p>

                    <div class="flex flex-col sm:flex-row gap-3.5 pt-2">
                        <a href="https://wa.me/6288985105537?text=Selamat%20siang%20Duta%20Teknik,%20saya%20ingin%20memanggil%20teknisi%20ke%20lokasi." target="_blank" class="inline-flex items-center justify-center gap-2.5 bg-emerald-500 hover:bg-emerald-600 text-slate-950 font-extrabold px-7 py-4 rounded-xl transition-all shadow-lg text-xs sm:text-sm">
                            <i class="fa-brands fa-whatsapp text-lg"></i>
                            <span>PANGGIL TEKNISI SEKARANG</span>
                        </a>
                        <a href="tel:088985105537" class="inline-flex items-center justify-center gap-2.5 bg-white/10 hover:bg-white/20 text-white border border-white/20 font-bold px-6 py-4 rounded-xl transition-all text-xs sm:text-sm backdrop-blur-sm">
                            <i class="fa-solid fa-phone text-sky-400"></i>
                            <span>0889-8510-5537</span>
                        </a>
                    </div>
                </div>

                <!-- Interactive Complaint Card -->
                <div class="lg:col-span-5 bg-white text-slate-900 rounded-3xl p-6 sm:p-8 bayangan-elegan border border-slate-200">
                    <div class="flex items-center gap-3 mb-2">
                        <div class="w-8 h-8 rounded-lg bg-sky-100 text-sky-600 flex items-center justify-center font-bold text-sm">
                            <i class="fa-solid fa-screwdriver-wrench"></i>
                        </div>
                        <h3 class="text-base font-extrabold text-slate-900">Pilih Kendala Pompa Air Anda</h3>
                    </div>
                    <p class="text-xs text-slate-500 mb-5">Klik keluhan di bawah ini untuk langsung terhubung ke WhatsApp teknisi:</p>

                    <div class="space-y-3 mb-6">
                        <button onclick="pilihKeluhan('Mesin pompa air mati total / berdengung')" class="w-full text-left p-3.5 rounded-xl border border-slate-200 hover:border-sky-600 hover:bg-sky-50/50 transition-all text-xs font-bold flex items-center justify-between group">
                            <span class="flex items-center gap-2.5 text-slate-800"><i class="fa-solid fa-triangle-exclamation text-sky-600 text-sm"></i> Mesin Mati Total / Berdengung</span>
                            <i class="fa-solid fa-chevron-right text-xs text-slate-400 group-hover:text-sky-600"></i>
                        </button>
                        <button onclick="pilihKeluhan('Mesin hidup tapi air tidak naik')" class="w-full text-left p-3.5 rounded-xl border border-slate-200 hover:border-sky-600 hover:bg-sky-50/50 transition-all text-xs font-bold flex items-center justify-between group">
                            <span class="flex items-center gap-2.5 text-slate-800"><i class="fa-solid fa-faucet-drip text-sky-600 text-sm"></i> Mesin Hidup, Air Tidak Naik</span>
                            <i class="fa-solid fa-chevron-right text-xs text-slate-400 group-hover:text-sky-600"></i>
                        </button>
                        <button onclick="pilihKeluhan('Otomatis cetak-cetek / berisik')" class="w-full text-left p-3.5 rounded-xl border border-slate-200 hover:border-sky-600 hover:bg-sky-50/50 transition-all text-xs font-bold flex items-center justify-between group">
                            <span class="flex items-center gap-2.5 text-slate-800"><i class="fa-solid fa-volume-high text-sky-600 text-sm"></i> Otomatis Cetak-Cetek / Berisik</span>
                            <i class="fa-solid fa-chevron-right text-xs text-slate-400 group-hover:text-sky-600"></i>
                        </button>
                        <button onclick="pilihKeluhan('Pembuatan sumur bor baru / kuras sumur')" class="w-full text-left p-3.5 rounded-xl border border-slate-200 hover:border-sky-600 hover:bg-sky-50/50 transition-all text-xs font-bold flex items-center justify-between group">
                            <span class="flex items-center gap-2.5 text-slate-800"><i class="fa-solid fa-bore-hole text-sky-600 text-sm"></i> Pembuatan Sumur Bor Baru</span>
                            <i class="fa-solid fa-chevron-right text-xs text-slate-400 group-hover:text-sky-600"></i>
                        </button>
                    </div>

                    <a id="tombolWaKeluhan" href="https://wa.me/6288985105537?text=Selamat%20siang%20Duta%20Teknik,%20saya%20ingin%20berkonsultasi%20mengenai%20perbaikan%20pompa%20air." target="_blank" class="w-full flex items-center justify-center gap-2.5 bg-emerald-600 hover:bg-emerald-700 text-white font-extrabold py-3.5 rounded-xl text-xs transition-all shadow-md">
                        <i class="fa-brands fa-whatsapp text-base"></i>
                        <span>KIRIM KELUHAN KE WHATSAPP</span>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <section id="keunggulan" class="py-20 bg-white border-b border-slate-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-2xl mx-auto mb-16">
                <span class="text-xs font-extrabold text-sky-600 uppercase tracking-widest bg-sky-50 px-3.5 py-1.5 rounded-full border border-sky-100">Standar Profesional</span>
                <h2 class="text-2xl sm:text-3xl font-extrabold text-slate-900 mt-3">Komitmen Pelayanan Terbaik</h2>
                <p class="text-slate-600 text-xs sm:text-sm mt-2">Kami mengutamakan kejujuran, ketepatan waktu, dan keahlian teknis tinggi dalam setiap pekerjaan.</p>
            </div>

            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-slate-50 p-8 rounded-2xl border border-slate-200 kartu-pro">
                    <div class="w-14 h-14 rounded-2xl bg-sky-100 text-sky-600 flex items-center justify-center text-2xl font-bold mb-6">
                        <i class="fa-solid fa-stopwatch"></i>
                    </div>
                    <h3 class="text-base font-extrabold text-slate-900 mb-2">Respon Cepat &amp; Tepat Waktu</h3>
                    <p class="text-slate-600 text-xs sm:text-sm leading-relaxed">
                        Teknisi siap siaga dipanggil dan datang tepat waktu ke lokasi Anda di seluruh wilayah Jakarta Selatan dan Tangerang Selatan.
                    </p>
                </div>

                <div class="bg-slate-50 p-8 rounded-2xl border border-slate-200 kartu-pro">
                    <div class="w-14 h-14 rounded-2xl bg-emerald-100 text-emerald-600 flex items-center justify-center text-2xl font-bold mb-6">
                        <i class="fa-solid fa-handshake-angle"></i>
                    </div>
                    <h3 class="text-base font-extrabold text-slate-900 mb-2">Biaya Transparan &amp; Jujur</h3>
                    <p class="text-slate-600 text-xs sm:text-sm leading-relaxed">
                        Pemeriksaan dilakukan secara teliti. Estimasi biaya perbaikan dan komponen disampaikan secara terbuka sebelum pengerjaan dimulai.
                    </p>
                </div>

                <div class="bg-slate-50 p-8 rounded-2xl border border-slate-200 kartu-pro">
                    <div class="w-14 h-14 rounded-2xl bg-amber-100 text-amber-600 flex items-center justify-center text-2xl font-bold mb-6">
                        <i class="fa-solid fa-shield-halved"></i>
                    </div>
                    <h3 class="text-base font-extrabold text-slate-900 mb-2">Garansi Pengerjaan Resmi</h3>
                    <p class="text-slate-600 text-xs sm:text-sm leading-relaxed">
                        Setiap tindakan servis dan penggantian suku cadang dilengkapi dengan garansi resmi demi kenyamanan dan ketenangan Anda.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <section id="layanan" class="py-20 bg-slate-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-2xl mx-auto mb-16">
                <span class="text-xs font-extrabold text-emerald-600 uppercase tracking-widest bg-emerald-50 px-3.5 py-1.5 rounded-full border border-emerald-100">Cakupan Jasa</span>
                <h2 class="text-2xl sm:text-3xl font-extrabold text-slate-900 mt-3">Layanan Utama Duta Teknik</h2>
                <p class="text-slate-600 text-xs sm:text-sm mt-2">Solusi komprehensif untuk permasalahan air bersih hunian, cluster, dan perkantoran.</p>
            </div>

            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-white p-8 rounded-2xl border border-slate-200 flex flex-col justify-between kartu-pro">
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-sky-600 text-white flex items-center justify-center text-lg font-bold mb-6 shadow-md">
                            <i class="fa-solid fa-screwdriver-wrench"></i>
                        </div>
                        <h3 class="text-base font-extrabold text-slate-900 mb-2">Servis Mesin Pompa Air</h3>
                        <p class="text-slate-600 text-xs sm:text-sm leading-relaxed mb-6">
                            Perbaikan total segala merek (Shimizu, Panasonic, Sanyo, Jet Pump), penggantian seal bocor, bearing, impeller, dan mengatasi masalah suara mesin bising.
                        </p>
                    </div>
                    <a href="https://wa.me/6288985105537?text=Selamat%20siang%20Duta%20Teknik,%20saya%20mau%20pesan%20servis%20pompa%20air." target="_blank" class="text-xs font-bold text-sky-600 hover:text-sky-700 flex items-center justify-between pt-4 border-t border-slate-100">
                        <span>Pesan Servis Pompa</span>
                        <i class="fa-solid fa-arrow-right text-xs"></i>
                    </a>
                </div>

                <div class="bg-white p-8 rounded-2xl border border-slate-200 flex flex-col justify-between kartu-pro">
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-sky-600 text-white flex items-center justify-center text-lg font-bold mb-6 shadow-md">
                            <i class="fa-solid fa-bore-hole"></i>
                        </div>
                        <h3 class="text-base font-extrabold text-slate-900 mb-2">Pembuatan Sumur Bor Baru</h3>
                        <p class="text-slate-600 text-xs sm:text-sm leading-relaxed mb-6">
                            Pengeboran sumur Jet Pump dan Submersible (Satelit) kedalaman dangkal hingga dalam untuk pasokan air jernih, bebas kuning, dan melimpah.
                        </p>
                    </div>
                    <a href="https://wa.me/6288985105537?text=Selamat%20siang%20Duta%20Teknik,%20saya%20mau%20konsultasi%20sumur%20bor." target="_blank" class="text-xs font-bold text-sky-600 hover:text-sky-700 flex items-center justify-between pt-4 border-t border-slate-100">
                        <span>Konsultasi Sumur Bor</span>
                        <i class="fa-solid fa-arrow-right text-xs"></i>
                    </a>
                </div>

                <div class="bg-white p-8 rounded-2xl border border-slate-200 flex flex-col justify-between kartu-pro">
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-sky-600 text-white flex items-center justify-center text-lg font-bold mb-6 shadow-md">
                            <i class="fa-solid fa-filter"></i>
                        </div>
                        <h3 class="text-base font-extrabold text-slate-900 mb-2">Filter &amp; Penjernih Air</h3>
                        <p class="text-slate-600 text-xs sm:text-sm leading-relaxed mb-6">
                            Pemasangan tabung filter air baru serta penggantian media pasir silika dan karbon aktif untuk mengatasi air kuning, keruh, berbau besi atau mangan.
                        </p>
                    </div>
                    <a href="https://wa.me/6288985105537?text=Selamat%20siang%20Duta%20Teknik,%20saya%20mau%20pasang%20filter%20air." target="_blank" class="text-xs font-bold text-sky-600 hover:text-sky-700 flex items-center justify-between pt-4 border-t border-slate-100">
                        <span>Pesan Filter Air</span>
                        <i class="fa-solid fa-arrow-right text-xs"></i>
                    </a>
                </div>

                <div class="bg-white p-8 rounded-2xl border border-slate-200 flex flex-col justify-between kartu-pro">
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-sky-600 text-white flex items-center justify-center text-lg font-bold mb-6 shadow-md">
                            <i class="fa-solid fa-bolt"></i>
                        </div>
                        <h3 class="text-base font-extrabold text-slate-900 mb-2">Gulung Dinamo Kawat Murni</h3>
                        <p class="text-slate-600 text-xs sm:text-sm leading-relaxed mb-6">
                            Gulung ulang kumparan kawat tembaga dinamo mesin pompa air yang terbakar akibat korsleting atau arus listrik rumah yang tidak stabil.
                        </p>
                    </div>
                    <a href="https://wa.me/6288985105537?text=Selamat%20siang%20Duta%20Teknik,%20saya%20mau%20gulung%20dinamo." target="_blank" class="text-xs font-bold text-sky-600 hover:text-sky-700 flex items-center justify-between pt-4 border-t border-slate-100">
                        <span>Informasi Gulung Dinamo</span>
                        <i class="fa-solid fa-arrow-right text-xs"></i>
                    </a>
                </div>

                <div class="bg-white p-8 rounded-2xl border border-slate-200 flex flex-col justify-between kartu-pro">
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-sky-600 text-white flex items-center justify-center text-lg font-bold mb-6 shadow-md">
                            <i class="fa-solid fa-faucet"></i>
                        </div>
                        <h3 class="text-base font-extrabold text-slate-900 mb-2">Instalasi Pipa &amp; Toren Air</h3>
                        <p class="text-slate-600 text-xs sm:text-sm leading-relaxed mb-6">
                            Pemasangan jalur perpipaan baru, perbaikan pipa mampet atau bocor di dalam tembok, serta instalasi penampungan air toren atas dan bawah.
                        </p>
                    </div>
                    <a href="https://wa.me/6288985105537?text=Selamat%20siang%20Duta%20Teknik,%20saya%20butuh%20instalasi%20pipa." target="_blank" class="text-xs font-bold text-sky-600 hover:text-sky-700 flex items-center justify-between pt-4 border-t border-slate-100">
                        <span>Pesan Instalasi Pipa</span>
                        <i class="fa-solid fa-arrow-right text-xs"></i>
                    </a>
                </div>

                <div class="bg-slate-900 text-white p-8 rounded-2xl flex flex-col justify-between shadow-lg">
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-emerald-500 text-slate-950 flex items-center justify-center text-lg font-bold mb-6 shadow-md">
                            <i class="fa-solid fa-headset"></i>
                        </div>
                        <h3 class="text-base font-extrabold mb-2">Punya Kendala Khusus Lainnya?</h3>
                        <p class="text-slate-300 text-xs sm:text-sm leading-relaxed mb-6">
                            Konsultasikan permasalahan mesin pompa air atau instalasi rumah Anda secara langsung dengan teknisi kami via WhatsApp sekarang juga.
                        </p>
                    </div>
                    <a href="https://wa.me/6288985105537?text=Selamat%20siang%20Duta%20Teknik,%20saya%20mau%20konsultasi%20kendala%20khusus%20pompa%20air." target="_blank" class="w-full flex items-center justify-center gap-2.5 bg-emerald-500 hover:bg-emerald-600 text-slate-950 font-extrabold py-3.5 rounded-xl text-xs transition-all shadow-md">
                        <i class="fa-brands fa-whatsapp text-base"></i>
                        <span>KONSULTASI VIA WHATSAPP</span>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <section id="wilayah" class="py-20 bg-white border-t border-slate-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-2xl mx-auto mb-16">
                <span class="text-xs font-extrabold text-sky-600 uppercase tracking-widest bg-sky-50 px-3.5 py-1.5 rounded-full border border-sky-100">Jangkauan Kerja</span>
                <h2 class="text-2xl sm:text-3xl font-extrabold text-slate-900 mt-3">Wilayah Layanan Jaksel &amp; Tangsel</h2>
                <p class="text-slate-600 text-xs sm:text-sm mt-2">Teknisi kami siap melayani panggilan cepat di seluruh kecamatan wilayah Jakarta Selatan dan Tangerang Selatan.</p>
            </div>

            <div class="grid md:grid-cols-2 gap-8">
                <div class="bg-slate-50 p-8 rounded-2xl border border-slate-200 kartu-pro">
                    <div class="flex items-center gap-4 mb-6 pb-4 border-b border-slate-200">
                        <div class="w-12 h-12 rounded-xl bg-sky-100 text-sky-700 flex items-center justify-center text-lg font-bold">
                            <i class="fa-solid fa-location-dot"></i>
                        </div>
                        <div>
                            <h3 class="text-base font-extrabold text-slate-900">Jakarta Selatan</h3>
                            <p class="text-xs text-slate-500">Panggilan Cepat Seluruh Kecamatan</p>
                        </div>
                    </div>
                    <div class="grid grid-cols-2 gap-3 text-xs text-slate-700 font-semibold">
                        <div class="flex items-center gap-2"><i class="fa-solid fa-check text-sky-600"></i> Kebayoran Baru &amp; Lama</div>
                        <div class="flex items-center gap-2"><i class="fa-solid fa-check text-sky-600"></i> Cilandak &amp; Pondok Indah</div>
                        <div class="flex items-center gap-2"><i class="fa-solid fa-check text-sky-600"></i> Jagakarsa &amp; Ciganjur</div>
                        <div class="flex items-center gap-2"><i class="fa-solid fa-check text-sky-600"></i> Pesanggrahan &amp; Bintaro</div>
                        <div class="flex items-center gap-2"><i class="fa-solid fa-check text-sky-600"></i> Pasar Minggu &amp; Kalibata</div>
                        <div class="flex items-center gap-2"><i class="fa-solid fa-check text-sky-600"></i> Mampang &amp; Pancoran</div>
                    </div>
                </div>

                <div class="bg-slate-50 p-8 rounded-2xl border border-slate-200 kartu-pro">
                    <div class="flex items-center gap-4 mb-6 pb-4 border-b border-slate-200">
                        <div class="w-12 h-12 rounded-xl bg-emerald-100 text-emerald-700 flex items-center justify-center text-lg font-bold">
                            <i class="fa-solid fa-city"></i>
                        </div>
                        <div>
                            <h3 class="text-base font-extrabold text-slate-900">Tangerang Selatan</h3>
                            <p class="text-xs text-slate-500">Komplek Perumahan &amp; Komersial</p>
                        </div>
                    </div>
                    <div class="grid grid-cols-2 gap-3 text-xs text-slate-700 font-semibold">
                        <div class="flex items-center gap-2"><i class="fa-solid fa-check text-emerald-600"></i> Bintaro Jaya (Sektor 1-9)</div>
                        <div class="flex items-center gap-2"><i class="fa-solid fa-check text-emerald-600"></i> BSD City &amp; Serpong</div>
                        <div class="flex items-center gap-2"><i class="fa-solid fa-check text-emerald-600"></i> Ciputat &amp; Ciputat Timur</div>
                        <div class="flex items-center gap-2"><i class="fa-solid fa-check text-emerald-600"></i> Pamulang &amp; Puspiptek</div>
                        <div class="flex items-center gap-2"><i class="fa-solid fa-check text-emerald-600"></i> Pondok Aren &amp; Jombang</div>
                        <div class="flex items-center gap-2"><i class="fa-solid fa-check text-emerald-600"></i> Serpong Utara &amp; Alam Sutera</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="tahapan" class="py-20 bg-slate-900 text-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-2xl mx-auto mb-16">
                <span class="text-xs font-extrabold text-sky-400 uppercase tracking-widest bg-slate-800 px-3.5 py-1.5 rounded-full border border-slate-700">Prosedur Layanan</span>
                <h2 class="text-2xl sm:text-3xl font-extrabold mt-3">Mudahnya Menggunakan Jasa Kami</h2>
                <p class="text-slate-400 text-xs sm:text-sm mt-2">Hanya 3 langkah mudah hingga air mengalir normal kembali di rumah Anda.</p>
            </div>

            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-slate-800 border border-slate-700 p-8 rounded-2xl relative">
                    <div class="text-4xl font-extrabold text-sky-400 mb-4 opacity-50">01</div>
                    <h3 class="text-base font-extrabold mb-2">Hubungi via WhatsApp</h3>
                    <p class="text-slate-400 text-xs sm:text-sm leading-relaxed">
                        Sampaikan keluhan pompa air Anda melalui WhatsApp. Tim kami merespon dengan cepat dan menjadwalkan kunjungan teknisi.
                    </p>
                </div>

                <div class="bg-slate-800 border border-slate-700 p-8 rounded-2xl relative">
                    <div class="text-4xl font-extrabold text-sky-400 mb-4 opacity-50">02</div>
                    <h3 class="text-base font-extrabold mb-2">Teknisi Datang &amp; Cek Lokasi</h3>
                    <p class="text-slate-400 text-xs sm:text-sm leading-relaxed">
                        Teknisi profesional kami datang tepat waktu, melakukan pengecekan menyeluruh, dan memberikan estimasi biaya transparan.
                    </p>
                </div>

                <div class="bg-slate-800 border border-slate-700 p-8 rounded-2xl relative">
                    <div class="text-4xl font-extrabold text-sky-400 mb-4 opacity-50">03</div>
                    <h3 class="text-base font-extrabold mb-2">Perbaikan &amp; Bergaransi</h3>
                    <p class="text-slate-400 text-xs sm:text-sm leading-relaxed">
                        Pekerjaan diselesaikan dengan rapi, diuji coba hingga air normal kembali, serta diberikan garansi resmi untuk ketenangan Anda.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <section id="faq" class="py-20 bg-white">
        <div class="max-w-3xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <span class="text-xs font-extrabold text-sky-600 uppercase tracking-widest bg-sky-50 px-3.5 py-1.5 rounded-full border border-sky-100">Informasi Umum</span>
                <h2 class="text-2xl sm:text-3xl font-extrabold text-slate-900 mt-3">Pertanyaan yang Sering Diajukan</h2>
            </div>

            <div class="space-y-4">
                <details class="bg-slate-50 rounded-2xl p-6 border border-slate-200 group [&amp;_summary::-webkit-details-marker]:hidden">
                    <summary class="flex items-center justify-between cursor-pointer font-extrabold text-slate-900 text-xs sm:text-sm">
                        <span>Berapa lama estimasi teknisi tiba di lokasi?</span>
                        <span class="transition-transform duration-200 group-open:-rotate-180 text-sky-600">
                            <i class="fa-solid fa-chevron-down text-xs"></i>
                        </span>
                    </summary>
                    <p class="mt-4 text-slate-600 text-xs sm:text-sm leading-relaxed border-t border-slate-200 pt-4">
                        Rata-rata waktu kedatangan teknisi adalah 30 hingga 60 menit setelah konfirmasi pesanan via WhatsApp, tergantung kondisi lalu lintas dan lokasi Anda di wilayah Jakarta Selatan atau Tangerang Selatan.
                    </p>
                </details>

                <details class="bg-slate-50 rounded-2xl p-6 border border-slate-200 group [&amp;_summary::-webkit-details-marker]:hidden">
                    <summary class="flex items-center justify-between cursor-pointer font-extrabold text-slate-900 text-xs sm:text-sm">
                        <span>Apakah ada garansi setelah perbaikan pompa air?</span>
                        <span class="transition-transform duration-200 group-open:-rotate-180 text-sky-600">
                            <i class="fa-solid fa-chevron-down text-xs"></i>
                        </span>
                    </summary>
                    <p class="mt-4 text-slate-600 text-xs sm:text-sm leading-relaxed border-t border-slate-200 pt-4">
                        Ya, setiap pekerjaan perbaikan maupun penggantian suku cadang utama mendapatkan garansi resmi dari Duta Teknik untuk menjamin kualitas pengerjaan dan kepuasan pelanggan.
                    </p>
                </details>

                <details class="bg-slate-50 rounded-2xl p-6 border border-slate-200 group [&amp;_summary::-webkit-details-marker]:hidden">
                    <summary class="flex items-center justify-between cursor-pointer font-extrabold text-slate-900 text-xs sm:text-sm">
                        <span>Bagaimana sistem pembayaran jasanya?</span>
                        <span class="transition-transform duration-200 group-open:-rotate-180 text-sky-600">
                            <i class="fa-solid fa-chevron-down text-xs"></i>
                        </span>
                    </summary>
                    <p class="mt-4 text-slate-600 text-xs sm:text-sm leading-relaxed border-t border-slate-200 pt-4">
                        Pembayaran dilakukan setelah pekerjaan selesai dan terbukti air mengalir dengan normal kembali. Pembayaran dapat dilakukan secara tunai maupun transfer bank resmi.
                    </p>
                </details>
            </div>
        </div>
    </section>

    <footer class="bg-slate-900 text-slate-400 text-xs py-14 border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid md:grid-cols-4 gap-10 mb-12">
                <div class="md:col-span-2 space-y-4">
                    <div class="flex items-center gap-3">
                        <div class="w-9 h-9 rounded-xl bg-sky-600 flex items-center justify-center text-white font-bold text-xs shadow-md">
                            <i class="fa-solid fa-water"></i>
                        </div>
                        <span class="text-base font-extrabold text-white tracking-tight">DUTA TEKNIK</span>
                    </div>
                    <p class="text-slate-400 max-w-sm leading-relaxed text-xs">
                        Layanan profesional spesialis perbaikan mesin pompa air, pembuatan sumur bor, dan instalasi filter air bersih untuk wilayah Jakarta Selatan dan Tangerang Selatan.
                    </p>
                </div>

                <div>
                    <h4 class="font-extrabold text-white uppercase tracking-wider mb-4 text-xs">Layanan Kami</h4>
                    <ul class="space-y-2.5">
                        <li><a href="#layanan" class="hover:text-white transition-colors">Servis Pompa Air</a></li>
                        <li><a href="#layanan" class="hover:text-white transition-colors">Sumur Bor Baru</a></li>
                        <li><a href="#layanan" class="hover:text-white transition-colors">Filter &amp; Penjernih Air</a></li>
                        <li><a href="#layanan" class="hover:text-white transition-colors">Gulung Dinamo</a></li>
                    </ul>
                </div>

                <div>
                    <h4 class="font-extrabold text-white uppercase tracking-wider mb-4 text-xs">Kontak Resmi</h4>
                    <p class="text-slate-300 font-semibold">Layanan Siaga Panggilan Teknisi</p>
                    <a href="tel:088985105537" class="text-sm font-extrabold text-sky-400 block mt-1.5 hover:underline">0889-8510-5537</a>
                    <p class="text-[11px] text-slate-500 mt-1">Area: Jaksel &amp; Tangsel</p>
                </div>
            </div>

            <div class="pt-8 border-t border-slate-800 text-center sm:flex sm:justify-between sm:items-center text-slate-500 text-[11px]">
                <p>© 2026 Duta Teknik. Hak Cipta Dilindungi Undang-Undang.</p>
                <button onclick="salinKodeHtml()" class="text-sky-400 hover:underline mt-2 sm:mt-0 font-bold">Download File HTML Lengkap</button>
            </div>
        </div>
    </footer>

    <div class="fixed bottom-0 left-0 right-0 z-50 md:hidden bg-white/95 backdrop-blur-md border-t border-slate-200 p-3 shadow-2xl">
        <div class="grid grid-cols-2 gap-2.5">
            <a href="tel:088985105537" class="flex items-center justify-center gap-2 bg-slate-100 text-slate-900 font-bold py-3 rounded-xl border border-slate-300 text-xs shadow-sm">
                <i class="fa-solid fa-phone text-sky-600"></i>
                <span>Telepon</span>
            </a>
            <a href="https://wa.me/6288985105537?text=Selamat%20siang%20Duta%20Teknik,%20saya%20mau%20panggil%20teknisi%20servis%20pompa%20air." target="_blank" class="flex items-center justify-center gap-2 bg-emerald-600 text-white font-extrabold py-3 rounded-xl text-xs shadow-md">
                <i class="fa-brands fa-whatsapp text-sm"></i>
                <span>WhatsApp</span>
            </a>
        </div>
    </div>

    <script>
        const tombolMenu = document.getElementById('tombolMenu');
        const menuPonsel = document.getElementById('menuPonsel');

        if (tombolMenu && menuPonsel) {
            tombolMenu.addEventListener('click', () => {
                menuPonsel.classList.toggle('hidden');
            });
            document.querySelectorAll('#menuPonsel a').forEach(tautan => {
                tautan.addEventListener('click', () => {
                    menuPonsel.classList.add('hidden');
                });
            });
        }

        function pilihKeluhan(teksKeluhan) {
            const tombolWaKeluhan = document.getElementById('tombolWaKeluhan');
            if (tombolWaKeluhan) {
                const nomorWa = "6288985105537";
                const pesanWa = `Selamat siang Duta Teknik, saya ingin berkonsultasi mengenai masalah pompa air:%0A*Kendala:* ${encodeURIComponent(teksKeluhan)}.%0AMohon bantuan teknisi untuk datang ke lokasi.`;
                tombolWaKeluhan.href = `https://wa.me/${nomorWa}?text=${pesanWa}`;
                
                tombolWaKeluhan.classList.add('ring-4', 'ring-emerald-300', 'scale-[1.02]');
                setTimeout(() => {
                    tombolWaKeluhan.classList.remove('ring-4', 'ring-emerald-300', 'scale-[1.02]');
                }, 800);
            }
        }

        function salinKodeHtml() {
            const htmlContent = document.documentElement.outerHTML;
            const blob = new Blob([htmlContent], { type: 'text/html;charset=utf-8' });
            const url = URL.createObjectURL(blob);
            const a = document.createElement('a');
            a.href = url;
            a.download = 'duta-teknik-pompa-air.html';
            document.body.appendChild(a);
            a.click();
            document.body.removeChild(a);
            URL.revokeObjectURL(url);
        }

        function salinKodePonsel() {
            const htmlContent = document.documentElement.outerHTML;
            const teksTombol = document.getElementById('teksTombolSalin');
            
            if (navigator.clipboard && navigator.clipboard.writeText) {
                navigator.clipboard.writeText(htmlContent).then(() => {
                    teksTombol.textContent = "Berhasil Disalin ke HP!";
                    setTimeout(() => { teksTombol.textContent = "Salin Kode HTML"; }, 3000);
                }).catch(() => {
                    fallbackSalin(htmlContent);
                });
            } else {
                fallbackSalin(htmlContent);
            }
        }

        function fallbackSalin(teks) {
            const textarea = document.createElement('textarea');
            textarea.value = teks;
            textarea.style.position = 'fixed';
            document.body.appendChild(textarea);
            textarea.focus();
            textarea.select();
            try {
                document.execCommand('copy');
                document.getElementById('teksTombolSalin').textContent = "Berhasil Disalin!";
                setTimeout(() => { document.getElementById('teksTombolSalin').textContent = "Salin Kode HTML"; }, 3000);
            } catch (err) {
                alert('Gagal menyalin otomatis. Silakan download file HTML lewat tombol di bawah.');
            }
            document.body.removeChild(textarea);
        }
    </script>

</body></html>
