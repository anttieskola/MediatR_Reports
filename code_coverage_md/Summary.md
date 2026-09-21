# Summary

|||
|:---|:---|
| Generated on: | 21.9.2026 - 17.18.28 |
| Parser: | Cobertura |
| Assemblies: | 1 |
| Classes: | 32 |
| Files: | 20 |
| **Line coverage:** | 91.1% (1130 of 1240) |
| Covered lines: | 1130 |
| Uncovered lines: | 110 |
| Coverable lines: | 1240 |
| Total lines: | 2148 |
| **Branch coverage:** | 82.3% (456 of 554) |
| Covered branches: | 456 |
| Total branches: | 554 |
| **Method coverage:** | [Feature is only available for sponsors](https://reportgenerator.io/pro) |

# Risk Hotspots

| **Assembly** | **Class** | **Method** | **Crap Score** | **Cyclomatic complexity** |
|:---|:---|:---|---:|---:|
| MediatR | MediatR.Internal.ObjectDetails | CompareByLocation(...) | 39 | 18 || MediatR | MediatR.Registration.ServiceRegistrar | FindInterfacesThatClosesCore() | 31 | 18 || MediatR | MediatR.Pipeline.RequestExceptionProcessorBehavior<TRequest, TResponse> | Handle() | 21 | 20 || MediatR | MediatR.Internal.ObjectDetails | CompareByNamespace(...) | 18 | 18 || MediatR | MediatR.Registration.ServiceRegistrar | ValidateCombinationsLimits(...) | 16 | 16 || MediatR | MediatR.Registration.ServiceRegistrar | AddRequiredServices(...) | 16 | 16 |
# Coverage

| **Name** | **Covered** | **Uncovered** | **Coverable** | **Total** | **Line coverage** | **Covered** | **Total** | **Branch coverage** |
|:---|---:|---:|---:|---:|---:|---:|---:|---:|
| **MediatR** | **1130** | **110** | **1240** | **3133** | **91.1%** | **456** | **554** | **82.3%** |
| MediatR.Entities.OpenBehavior | 16 | 0 | 16 | 56 | 100% | 8 | 8 | 100% |
| MediatR.Internal.HandlersOrderer | 25 | 5 | 30 | 50 | 83.3% | 17 | 20 | 85% |
| MediatR.Internal.HandlersOrderer<TRequest> | 25 | 5 | 30 | 50 | 83.3% | 17 | 20 | 85% |
| MediatR.Internal.ObjectDetails | 47 | 6 | 53 | 128 | 88.6% | 51 | 58 | 87.9% |
| MediatR.Mediator | 96 | 9 | 105 | 172 | 91.4% | 31 | 44 | 70.4% |
| MediatR.Mediator<TRequest> | 96 | 9 | 105 | 172 | 91.4% | 31 | 44 | 70.4% |
| MediatR.Mediator<TResponse> | 96 | 9 | 105 | 172 | 91.4% | 31 | 44 | 70.4% |
| MediatR.NotificationHandler<TNotification> | 4 | 0 | 4 | 40 | 100% | 0 | 0 |  |
| MediatR.NotificationHandlerExecutor | 1 | 0 | 1 | 7 | 100% | 0 | 0 |  |
| MediatR.NotificationPublishers.ForeachAwaitPublisher | 6 | 0 | 6 | 24 | 100% | 2 | 2 | 100% |
| MediatR.NotificationPublishers.TaskWhenAllPublisher | 4 | 0 | 4 | 22 | 100% | 0 | 0 |  |
| MediatR.Pipeline.RequestExceptionActionProcessorBehavior<TRequest, TResponse> | 16 | 0 | 16 | 88 | 100% | 1 | 2 | 50% |
| MediatR.Pipeline.RequestExceptionActionProcessorBehavior<TRequest, TResponse> | 29 | 5 | 34 | 88 | 85.2% | 13 | 16 | 81.2% |
| MediatR.Pipeline.RequestExceptionHandlerState<TResponse> | 4 | 0 | 4 | 28 | 100% | 0 | 0 |  |
| MediatR.Pipeline.RequestExceptionProcessorBehavior<TRequest, TResponse> | 13 | 0 | 13 | 101 | 100% | 1 | 2 | 50% |
| MediatR.Pipeline.RequestExceptionProcessorBehavior<TRequest, TResponse> | 40 | 5 | 45 | 101 | 88.8% | 18 | 24 | 75% |
| MediatR.Pipeline.RequestPostProcessorBehavior<TRequest, TResponse> | 1 | 0 | 1 | 25 | 100% | 0 | 0 |  |
| MediatR.Pipeline.RequestPostProcessorBehavior<TRequest, TResponse> | 8 | 0 | 8 | 25 | 100% | 2 | 2 | 100% |
| MediatR.Pipeline.RequestPreProcessorBehavior<TRequest, TResponse> | 1 | 0 | 1 | 23 | 100% | 0 | 0 |  |
| MediatR.Pipeline.RequestPreProcessorBehavior<TRequest, TResponse> | 7 | 0 | 7 | 23 | 100% | 2 | 2 | 100% |
| MediatR.Registration.ServiceRegistrar | 296 | 30 | 326 | 473 | 90.7% | 147 | 164 | 89.6% |
| MediatR.Unit | 27 | 0 | 27 | 145 | 100% | 0 | 0 |  |
| MediatR.Wrappers.NotificationHandlerWrapperImpl<TNotification> | 1 | 0 | 1 | 34 | 100% | 0 | 0 |  |
| MediatR.Wrappers.NotificationHandlerWrapperImpl<TNotification> | 5 | 0 | 5 | 34 | 100% | 2 | 2 | 100% |
| MediatR.Wrappers.RequestHandlerWrapperImpl<TRequest, TResponse> | 6 | 0 | 6 | 79 | 100% | 0 | 0 |  |
| MediatR.Wrappers.RequestHandlerWrapperImpl<TRequest, TResponse> | 13 | 0 | 13 | 79 | 100% | 8 | 8 | 100% |
| MediatR.Wrappers.RequestHandlerWrapperImpl<TRequest> | 6 | 0 | 6 | 79 | 100% | 0 | 0 |  |
| MediatR.Wrappers.RequestHandlerWrapperImpl<TRequest> | 13 | 0 | 13 | 79 | 100% | 8 | 8 | 100% |
| MediatR.Wrappers.StreamRequestHandlerWrapperImpl<TRequest, TResponse, T> | 37 | 0 | 37 | 83 | 100% | 3 | 6 | 50% |
| MediatR.Wrappers.StreamRequestHandlerWrapperImpl<TRequest, TResponse> | 37 | 0 | 37 | 83 | 100% | 3 | 6 | 50% |
| Microsoft.Extensions.DependencyInjection.MediatRServiceConfiguration | 140 | 27 | 167 | 511 | 83.8% | 58 | 70 | 82.8% |
| Microsoft.Extensions.DependencyInjection.ServiceCollectionExtensions | 14 | 0 | 14 | 59 | 100% | 2 | 2 | 100% |

