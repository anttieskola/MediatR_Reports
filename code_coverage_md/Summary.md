# Summary

|||
|:---|:---|
| Generated on: | 17.9.2026 - 19.00.26 |
| Parser: | Cobertura |
| Assemblies: | 1 |
| Classes: | 32 |
| Files: | 20 |
| **Line coverage:** | 87.7% (1107 of 1261) |
| Covered lines: | 1107 |
| Uncovered lines: | 154 |
| Coverable lines: | 1261 |
| Total lines: | 2119 |
| **Branch coverage:** | 76.7% (453 of 590) |
| Covered branches: | 453 |
| Total branches: | 590 |
| **Method coverage:** | [Feature is only available for sponsors](https://reportgenerator.io/pro) |

# Risk Hotspots

| **Assembly** | **Class** | **Method** | **Crap Score** | **Cyclomatic complexity** |
|:---|:---|:---|---:|---:|
| MediatR | MediatR.Internal.ObjectDetails | CompareByLocation(...) | 342 | 18 || MediatR | MediatR.Internal.ObjectDetails | CompareByNamespace(...) | 51 | 18 || MediatR | MediatR.Entities.OpenBehavior | ValidatePipelineBehaviorType(...) | 42 | 6 || MediatR | MediatR.Registration.ServiceRegistrar | FindInterfacesThatClosesCore() | 32 | 18 || MediatR | MediatR.Registration.ServiceRegistrar | ConnectImplementationsToTypesClosing(...) | 24 | 24 || MediatR | MediatR.Registration.ServiceRegistrar | GenerateCombinations(...) | 24 | 24 || MediatR | MediatR.Pipeline.RequestExceptionProcessorBehavior<TRequest, TResponse> | Handle() | 21 | 20 || MediatR | MediatR.Registration.ServiceRegistrar | AddRequiredServices(...) | 16 | 16 |
# Coverage

| **Name** | **Covered** | **Uncovered** | **Coverable** | **Total** | **Line coverage** | **Covered** | **Total** | **Branch coverage** |
|:---|---:|---:|---:|---:|---:|---:|---:|---:|
| **MediatR** | **1107** | **154** | **1261** | **3135** | **87.7%** | **453** | **590** | **76.7%** |
| MediatR.Entities.OpenBehavior | 0 | 14 | 14 | 53 | 0% | 0 | 8 | 0% |
| MediatR.Internal.HandlersOrderer | 25 | 5 | 30 | 50 | 83.3% | 17 | 20 | 85% |
| MediatR.Internal.HandlersOrderer<TRequest> | 25 | 5 | 30 | 50 | 83.3% | 17 | 20 | 85% |
| MediatR.Internal.ObjectDetails | 28 | 35 | 63 | 145 | 44.4% | 20 | 58 | 34.4% |
| MediatR.Mediator | 108 | 10 | 118 | 200 | 91.5% | 43 | 56 | 76.7% |
| MediatR.Mediator<TRequest> | 108 | 10 | 118 | 200 | 91.5% | 43 | 56 | 76.7% |
| MediatR.Mediator<TResponse> | 108 | 10 | 118 | 200 | 91.5% | 43 | 56 | 76.7% |
| MediatR.NotificationHandler<TNotification> | 4 | 0 | 4 | 40 | 100% | 0 | 0 |  |
| MediatR.NotificationHandlerExecutor | 1 | 0 | 1 | 7 | 100% | 0 | 0 |  |
| MediatR.NotificationPublishers.ForeachAwaitPublisher | 6 | 0 | 6 | 24 | 100% | 2 | 2 | 100% |
| MediatR.NotificationPublishers.TaskWhenAllPublisher | 6 | 0 | 6 | 28 | 100% | 0 | 0 |  |
| MediatR.Pipeline.RequestExceptionActionProcessorBehavior<TRequest, TResponse> | 15 | 0 | 15 | 91 | 100% | 1 | 2 | 50% |
| MediatR.Pipeline.RequestExceptionActionProcessorBehavior<TRequest, TResponse> | 29 | 5 | 34 | 91 | 85.2% | 13 | 16 | 81.2% |
| MediatR.Pipeline.RequestExceptionHandlerState<TResponse> | 4 | 0 | 4 | 28 | 100% | 0 | 0 |  |
| MediatR.Pipeline.RequestExceptionProcessorBehavior<TRequest, TResponse> | 13 | 0 | 13 | 102 | 100% | 1 | 2 | 50% |
| MediatR.Pipeline.RequestExceptionProcessorBehavior<TRequest, TResponse> | 40 | 5 | 45 | 102 | 88.8% | 18 | 24 | 75% |
| MediatR.Pipeline.RequestPostProcessorBehavior<TRequest, TResponse> | 1 | 0 | 1 | 26 | 100% | 0 | 0 |  |
| MediatR.Pipeline.RequestPostProcessorBehavior<TRequest, TResponse> | 8 | 0 | 8 | 26 | 100% | 2 | 2 | 100% |
| MediatR.Pipeline.RequestPreProcessorBehavior<TRequest, TResponse> | 1 | 0 | 1 | 24 | 100% | 0 | 0 |  |
| MediatR.Pipeline.RequestPreProcessorBehavior<TRequest, TResponse> | 7 | 0 | 7 | 24 | 100% | 2 | 2 | 100% |
| MediatR.Registration.ServiceRegistrar | 293 | 28 | 321 | 451 | 91.2% | 147 | 164 | 89.6% |
| MediatR.Unit | 11 | 0 | 11 | 96 | 100% | 0 | 0 |  |
| MediatR.Wrappers.NotificationHandlerWrapperImpl<TNotification> | 1 | 0 | 1 | 30 | 100% | 0 | 0 |  |
| MediatR.Wrappers.NotificationHandlerWrapperImpl<TNotification> | 5 | 0 | 5 | 30 | 100% | 2 | 2 | 100% |
| MediatR.Wrappers.RequestHandlerWrapperImpl<TRequest, TResponse> | 6 | 0 | 6 | 72 | 100% | 0 | 0 |  |
| MediatR.Wrappers.RequestHandlerWrapperImpl<TRequest, TResponse> | 11 | 0 | 11 | 72 | 100% | 8 | 8 | 100% |
| MediatR.Wrappers.RequestHandlerWrapperImpl<TRequest> | 6 | 0 | 6 | 72 | 100% | 0 | 0 |  |
| MediatR.Wrappers.RequestHandlerWrapperImpl<TRequest> | 11 | 0 | 11 | 72 | 100% | 8 | 8 | 100% |
| MediatR.Wrappers.StreamRequestHandlerWrapperImpl<TRequest, TResponse, T> | 35 | 0 | 35 | 77 | 100% | 3 | 6 | 50% |
| MediatR.Wrappers.StreamRequestHandlerWrapperImpl<TRequest, TResponse> | 35 | 0 | 35 | 77 | 100% | 3 | 6 | 50% |
| Microsoft.Extensions.DependencyInjection.MediatRServiceConfiguration | 142 | 27 | 169 | 515 | 84% | 58 | 70 | 82.8% |
| Microsoft.Extensions.DependencyInjection.ServiceCollectionExtensions | 14 | 0 | 14 | 60 | 100% | 2 | 2 | 100% |

