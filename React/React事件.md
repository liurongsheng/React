# React 事件
```
// Clipboard Events
onCopy?: ClipboardEventHandler<T>;
onCopyCapture?: ClipboardEventHandler<T>;
onCut?: ClipboardEventHandler<T>;
onCutCapture?: ClipboardEventHandler<T>;
onPaste?: ClipboardEventHandler<T>;
onPasteCapture?: ClipboardEventHandler<T>;

// Composition Events
onCompositionEnd?: CompositionEventHandler<T>;
onCompositionEndCapture?: CompositionEventHandler<T>;
onCompositionStart?: CompositionEventHandler<T>;
onCompositionStartCapture?: CompositionEventHandler<T>;
onCompositionUpdate?: CompositionEventHandler<T>;
onCompositionUpdateCapture?: CompositionEventHandler<T>;

// Focus Events
onFocus?: FocusEventHandler<T>;
onFocusCapture?: FocusEventHandler<T>;
onBlur?: FocusEventHandler<T>;
onBlurCapture?: FocusEventHandler<T>;

// Form Events
onChange?: FormEventHandler<T>;
onChangeCapture?: FormEventHandler<T>;
onInput?: FormEventHandler<T>;
onInputCapture?: FormEventHandler<T>;
onReset?: FormEventHandler<T>;
onResetCapture?: FormEventHandler<T>;
onSubmit?: FormEventHandler<T>;
onSubmitCapture?: FormEventHandler<T>;
onInvalid?: FormEventHandler<T>;
onInvalidCapture?: FormEventHandler<T>;

// Image Events
onLoad?: ReactEventHandler<T>;
onLoadCapture?: ReactEventHandler<T>;
onError?: ReactEventHandler<T>; // also a Media Event
onErrorCapture?: ReactEventHandler<T>; // also a Media Event

// Keyboard Events
onKeyDown?: KeyboardEventHandler<T>;
onKeyDownCapture?: KeyboardEventHandler<T>;
onKeyPress?: KeyboardEventHandler<T>;
onKeyPressCapture?: KeyboardEventHandler<T>;
onKeyUp?: KeyboardEventHandler<T>;
onKeyUpCapture?: KeyboardEventHandler<T>;

// Media Events
onAbort?: ReactEventHandler<T>;
onAbortCapture?: ReactEventHandler<T>;
onCanPlay?: ReactEventHandler<T>;
onCanPlayCapture?: ReactEventHandler<T>;
onCanPlayThrough?: ReactEventHandler<T>;
onCanPlayThroughCapture?: ReactEventHandler<T>;
onDurationChange?: ReactEventHandler<T>;
onDurationChangeCapture?: ReactEventHandler<T>;
onEmptied?: ReactEventHandler<T>;
onEmptiedCapture?: ReactEventHandler<T>;
onEncrypted?: ReactEventHandler<T>;
onEncryptedCapture?: ReactEventHandler<T>;
onEnded?: ReactEventHandler<T>;
onEndedCapture?: ReactEventHandler<T>;
onLoadedData?: ReactEventHandler<T>;
onLoadedDataCapture?: ReactEventHandler<T>;
onLoadedMetadata?: ReactEventHandler<T>;
onLoadedMetadataCapture?: ReactEventHandler<T>;
onLoadStart?: ReactEventHandler<T>;
onLoadStartCapture?: ReactEventHandler<T>;
onPause?: ReactEventHandler<T>;
onPauseCapture?: ReactEventHandler<T>;
onPlay?: ReactEventHandler<T>;
onPlayCapture?: ReactEventHandler<T>;
onPlaying?: ReactEventHandler<T>;
onPlayingCapture?: ReactEventHandler<T>;
onProgress?: ReactEventHandler<T>;
onProgressCapture?: ReactEventHandler<T>;
onRateChange?: ReactEventHandler<T>;
onRateChangeCapture?: ReactEventHandler<T>;
onSeeked?: ReactEventHandler<T>;
onSeekedCapture?: ReactEventHandler<T>;
onSeeking?: ReactEventHandler<T>;
onSeekingCapture?: ReactEventHandler<T>;
onStalled?: ReactEventHandler<T>;
onStalledCapture?: ReactEventHandler<T>;
onSuspend?: ReactEventHandler<T>;
onSuspendCapture?: ReactEventHandler<T>;
onTimeUpdate?: ReactEventHandler<T>;
onTimeUpdateCapture?: ReactEventHandler<T>;
onVolumeChange?: ReactEventHandler<T>;
onVolumeChangeCapture?: ReactEventHandler<T>;
onWaiting?: ReactEventHandler<T>;
onWaitingCapture?: ReactEventHandler<T>;

// MouseEvents
onClick?: MouseEventHandler<T>;
onClickCapture?: MouseEventHandler<T>;
onContextMenu?: MouseEventHandler<T>;
onContextMenuCapture?: MouseEventHandler<T>;
onDoubleClick?: MouseEventHandler<T>;
onDoubleClickCapture?: MouseEventHandler<T>;
onDrag?: DragEventHandler<T>;
onDragCapture?: DragEventHandler<T>;
onDragEnd?: DragEventHandler<T>;
onDragEndCapture?: DragEventHandler<T>;
onDragEnter?: DragEventHandler<T>;
onDragEnterCapture?: DragEventHandler<T>;
onDragExit?: DragEventHandler<T>;
onDragExitCapture?: DragEventHandler<T>;
onDragLeave?: DragEventHandler<T>;
onDragLeaveCapture?: DragEventHandler<T>;
onDragOver?: DragEventHandler<T>;
onDragOverCapture?: DragEventHandler<T>;
onDragStart?: DragEventHandler<T>;
onDragStartCapture?: DragEventHandler<T>;
onDrop?: DragEventHandler<T>;
onDropCapture?: DragEventHandler<T>;
onMouseDown?: MouseEventHandler<T>;
onMouseDownCapture?: MouseEventHandler<T>;
onMouseEnter?: MouseEventHandler<T>;
onMouseLeave?: MouseEventHandler<T>;
onMouseMove?: MouseEventHandler<T>;
onMouseMoveCapture?: MouseEventHandler<T>;
onMouseOut?: MouseEventHandler<T>;
onMouseOutCapture?: MouseEventHandler<T>;
onMouseOver?: MouseEventHandler<T>;
onMouseOverCapture?: MouseEventHandler<T>;
onMouseUp?: MouseEventHandler<T>;
onMouseUpCapture?: MouseEventHandler<T>;

// Selection Events
onSelect?: ReactEventHandler<T>;
onSelectCapture?: ReactEventHandler<T>;

// Touch Events
onTouchCancel?: TouchEventHandler<T>;
onTouchCancelCapture?: TouchEventHandler<T>;
onTouchEnd?: TouchEventHandler<T>;
onTouchEndCapture?: TouchEventHandler<T>;
onTouchMove?: TouchEventHandler<T>;
onTouchMoveCapture?: TouchEventHandler<T>;
onTouchStart?: TouchEventHandler<T>;
onTouchStartCapture?: TouchEventHandler<T>;

// Pointer Events
onPointerDown?: PointerEventHandler<T>;
onPointerDownCapture?: PointerEventHandler<T>;
onPointerMove?: PointerEventHandler<T>;
onPointerMoveCapture?: PointerEventHandler<T>;
onPointerUp?: PointerEventHandler<T>;
onPointerUpCapture?: PointerEventHandler<T>;
onPointerCancel?: PointerEventHandler<T>;
onPointerCancelCapture?: PointerEventHandler<T>;
onPointerEnter?: PointerEventHandler<T>;
onPointerEnterCapture?: PointerEventHandler<T>;
onPointerLeave?: PointerEventHandler<T>;
onPointerLeaveCapture?: PointerEventHandler<T>;
onPointerOver?: PointerEventHandler<T>;
onPointerOverCapture?: PointerEventHandler<T>;
onPointerOut?: PointerEventHandler<T>;
onPointerOutCapture?: PointerEventHandler<T>;
onGotPointerCapture?: PointerEventHandler<T>;
onGotPointerCaptureCapture?: PointerEventHandler<T>;
onLostPointerCapture?: PointerEventHandler<T>;
onLostPointerCaptureCapture?: PointerEventHandler<T>;

// UI Events
onScroll?: UIEventHandler<T>;
onScrollCapture?: UIEventHandler<T>;

// Wheel Events
onWheel?: WheelEventHandler<T>;
onWheelCapture?: WheelEventHandler<T>;

// Animation Events
onAnimationStart?: AnimationEventHandler<T>;
onAnimationStartCapture?: AnimationEventHandler<T>;
onAnimationEnd?: AnimationEventHandler<T>;
onAnimationEndCapture?: AnimationEventHandler<T>;
onAnimationIteration?: AnimationEventHandler<T>;
onAnimationIterationCapture?: AnimationEventHandler<T>;

// Transition Events
onTransitionEnd?: TransitionEventHandler<T>;
onTransitionEndCapture?: TransitionEventHandler<T>;
```
