---
title: "Live events in Yammer"
ms.author: v-irpast
author: IrenePasternack
manager: pamgreen
ms.date: 3/1/2019
ms.audience: Admin
ms.topic: overview
ms.service: yammer
localization_priority: Normal
ms.custom: Adm_Yammer
search.appverid:
- MET150
- MOP150
- MOE150
- MEW150
- MED150
ms.assetid: 4ece0ee2-c268-4636-bf2a-16e454befe57
description: "Learn what's needed to host live video events for Yammer users."
---
# Live events in Yammer

> [!NOTE]
> The information in this topic applies to the public preview release of live events supported by Yammer, Teams, and Stream.

Yammer is where communities thrive - a community centered around leaders engaging with their employees, a community of common interest, a community of people who share an identity, or a community of learning and shared practices. To bring the members of a community together centered around an event, Yammer group admins can host a live video event using Yammer, Microsoft Teams, and Microsoft Stream. Each live event includes Yammer conversations before, during, and after the event.

Due to the open nature of Yammer conversations, Yammer is particularly well-suited to foster connection and engagement between leaders and employees at every level in your organization. Hosting your next live event in your Leadership Connection community is a great way for leadership teams to drive alignment of your people around shared purpose and goals. Leaders realize that organizations who do this well have an advantage in attracting and retaining an engaged workforce.

You can create a public group to reach all employees, or use a private group so that only those with membership in the group can participate. Before the event, you have a place in Yammer to direct employees and/or group members to where you can show preview clips to generate buzz, announce an open call for questions in a Q&A segment, or just a place for people to chat about the upcoming event. 

Following an event, it’s easy to make the recording available on the event page, allowing employees to watch the event on their own schedule. For employees who are in different time zones or unable to attend live, the conversation keeps going so they still feel connected to leaders and peers, helping to overcome geographical or organizational boundaries.

For information about what a live event in Yammer looks like, see [Attend a live event in Yammer](https://support.office.com/article/attend-a-live-event-in-yammer-4b08133c-9ebb-47b0-ab60-4dbfd4bfc965). 

For steps to create a live event in Yammer, see [Organize a live event in Yammer](https://support.office.com/article/organize-a-live-event-in-yammer-105dd7af-9caf-4a5e-8a44-56d203e96551).

## Live event overview

To understand how Yammer, Stream, and Teams work together in live events, see [Overview of live events](https://docs.microsoft.com/microsoftteams/teams-live-events/what-are-teams-live-events#overview).

Live events can be created and viewed in Yammer, Stream, or Teams. This article explains the requirements for creating and viewing a live event in Yammer. 

There are two ways live events can be produced. The requirements for using live events in Yammer depend on which video production methods you intend to use in your organization.

- Produce your live event in Teams, and use Teams to share content from the presenter's webcams and screens. This is used for simple events when all you need is the audio and video devices connected to the PC, or when you're inviting a remote presenter for the event. Presenters use their own web cams and can share their screen as input for the event. This type of event requires use of Teams.
> [!NOTE]
> These events are in preview in Yammer. Attendees can't watch them there yet. For now, they can watch and comment in Microsoft Teams, or follow the conversation in Yammer.

- Produce your live event with external video input. This type of event is typically used for large scale events such as executive town halls, where a single stream from a media mixer is broadcasted to the audience. This type of event requires use of Stream.

## Yammer network requirements

 - To host a live event in Yammer, your organization must have **Enforce Office 365 identity** selected, and you must be using Office 365 connected groups. For more information see [Enforce Office 365 identity for Yammer users](../configure-your-yammer-network/enforce-office-365-identity.md) and [Yammer and Office 365 groups](../manage-yammer-groups/yammer-and-office-365-groups.md).

- You must have either a public Yammer Office 365 connected group, or a private Yammer Office 365 connected group that includes everyone who will be invited to the live event. For more information, see [Create a group in Yammer](https://support.office.com/en-us/article/create-a-group-in-yammer-b407af4f-9a58-4b12-b43e-afbb1b07c889) and [Manage a group in Yammer](https://support.office.com/en-us/article/manage-a-group-in-yammer-6e05c6d6-5548-4c88-89cd-e6757a514ef2). The All Company group can’t be used for live events.

## Requirements for live event attendees

- Everyone who attends a Yammer live event must have an Office 365 subscription that includes a license for Yammer (Office 365 A3, A5, F1, E1, E3, or E5).

- Everyone with a Yammer license can attend live events in public groups. For live events in private groups, attendees must be members of the private group in which the live event is hosted. 

## Permissions for scheduling, creating, and producing live events in Yammer

Who can create and produce live events is controlled by Stream and Teams settings and licenses. These permissions are not controlled in Yammer settings. The requirements depend on the production methods you plan to use.

A Teams license is required to schedule a Yammer live event.

- **Events produced in Teams**:
    The person who presents or produces the event must have a Teams license and specific policies set in Teams. For requirements, see [Who can create and schedule live events in Teams](https://docs.microsoft.com/microsoftteams/teams-live-events/plan-for-teams-live-events#who-can-create-and-schedule-live-events). For steps to set policies, see [Set up live events policies](https://docs.microsoft.com/microsoftteams/teams-live-events/set-up-for-teams-live-events#step-3-set-up-live-events-policies). 

- **Events produced externally**:
    For events that use a tool other than Teams to share content, the person who presents or produces the event must have a Stream license and permission to create live events. By default, only Microsoft Stream administrators have permission to create live events. Use the Stream admin settings to give permission to specific users. For steps to grant or remove permissions in Stream, see [Administration controls for live events in Stream](https://docs.microsoft.com/en-us/stream/live-event-administration).
 
### Restrict creation of live events in Yammer

You can prevent creation of live events produced in teams, live events produced with other tools, or both.

- To prevent creation of live events produced in Teams, remove permissions in Teams for live event scheduling. If a user does not have a license or permission to create a live event in Teams, when they create a live event in Yammer, the produce in Teams option is unavailable.

- To prevent external production for live events, don't give Stream permissions to any users. If a user does not have a license or permission to create a live event in Stream, when they try to create a live event in Yammer, the external production option is are unavailable.

- To prevent both types of live events, make sure Yammer users do not have permission to create live events in Teams and in Stream.

## See also

[Organize a live event in Yammer](https://support.office.com/article/organize-a-live-event-in-yammer-105dd7af-9caf-4a5e-8a44-56d203e96551)

[Microsoft Teams live event overview](https://support.office.com/article/microsoft-teams-live-events-overview-d077fec2-a058-483e-9ab5-1494afda578a?ui=en-US&rs=en-US&ad=US)

[Microsoft Stream live event overview](https://docs.microsoft.com/en-us/stream/live-event-overview)